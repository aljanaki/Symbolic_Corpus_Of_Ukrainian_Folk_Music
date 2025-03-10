Metadata
=====

**Metadata** files, which describe every song in the corpus, are located in the metadata folder. They are sorted by song cycle (Ritual, Non-ritual, and Children's songs).
One important aspect is the genre of the song, which is encoded using an abbreviation, explained   
`in this document <https://github.com/aljanaki/Symbolic_Corpus_Of_Ukrainian_Folk_Music/blob/8fd2c6daff9c921a50786b5dc72a5ac2ba1ee4d1/docs/attachments/Catalogue%20of%20Ukrainian%20Song%20Folklore.pdf>`_ for this codes.


Here is a list of all the columns in the metadata files with their meaning:


.. list-table::
   :header-rows: 1

   * - Metadata Column
     - Description
     - Example Value
   * - Filename
     - Filename in format “Region_nr_title”
     - Vinnytsia_321_Oi nashi khloptsi nedbailytsi
   * - Name in catalogue
     - Reference to Efremova created catalogue which encodes information about a song
     - ОК-КП-05
   * - Original title
     - Title of the song in Ukrainian
     - Ой наші хлопці недбайлиці 
   * - Transliterated title
     - Song title automatically transliterated to latin alphabet
     - Oi nashi khloptsi nedbailytsi
   * - Type
     - Whether song belongs to Ritual, Non-ritual or children’s songs
     - Ritual
   * - Year
     - Year when the song was recorded and transcribed
     - 1972
   * - Collector
     - Who recorded the song in the field from folk music performer
     - Василенко Зоя, Рубай Галина, Довженок Галина
   * - Place
     - The place where the song was recorded (usually, a village)
     - с. Дмитренки Гайсинського р-ну Вінницької обл.
   * - Latitude, longitude
     - Geocoded coordinates of the place (mostly using Google Maps API)
     - 47.86, 27,13
   * - Performer
     - Who performed the song
     - Колесниченко Ганна Іванівна, 1906 р.н.   
   * - Number of voices
     - How many voices the song has (manually annotated by a musicologist)
     - unison	 
   * - Performer gender or age
     - What was performer’s gender and/or age, manually annotated using the available archival reference. May or may not coincide who the song is intended to be performed by.
     - woman	 
   * - Audio recording
     - Reference to analogue sound recording in archive (only available for 7% of the songs)
     - фонозапис ф. 14-10, од. зб. 1248, № 9.	 
   * - Additional remarks
     - Any other information about a song: it’s ritual function, performative aspects, singer background. Manually extracted from archival reference.
     - Співають дівчата на Великдень, зібравшись в гурточок	 
   * - Archive reference
     - Reference to where the physical copy of the sheet music and audio recording (if available) is stored
     - ІМФЕ, ф. 14-5, од. зб. 424, арк. 136-137; фонозапис ф. 14-10, од. зб. 1248, № 9. Транскрибування:  Василенко З. І.
