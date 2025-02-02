Metadata
=====

**Metadata** files, describing every song in the corpus, are in metadata folder, sorted by the type of song (Ritual, Non-ritual (Calendar-Ritual and Family-Ritual) and children's songs.   
One of the important parts is genre of the song, which is encoded in two-letter codes. Here is the `disambiguation <https://github.com/aljanaki/Symbolic_Corpus_Of_Ukrainian_Folk_Music/blob/main/docs/attachments/Catalogue%of%Ukrainian%Song%Folklore.pdf>`_ for this codes.

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
