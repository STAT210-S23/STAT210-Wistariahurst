This is a location for the scans and curated materials from the Bachelder World War II era letters.

The Bachelder Letters Collection contains 135 documents, comprised of mostly letters but also telegrams. According to Penni Martorell, 76 of these letters are from Walter Frederick (Fred) Bachelder to his mother Selma Bachelder. The rest are from Julia Bachelder (minus a few signed by his daughter Susan). The early letters are handwritten, but several of the latter letters are typed. The collection spans many years (1927-1953), but there are also some letters/telegrams that are undated. There is only one letter from the 1930s (written by Julia to her mother in 1932). Interestingly, some of the letters have parts that are cut out or whited out. For example, on December 8, 1943 Fred writes to his mother telling him where he has been moved, yet the part where he writes the location is covered with whiteout.

Currently, the Holyoke Collection Finding Aid includes a subseries on the Bachelder Family (Subseries B). In this subseries are letters from Julia Bachelder to her friends and family, day planners, gold score cards, postcards to Julia and Mrs. WF Bachelder, sympathy cards, and a scrapbook of Julia Bachelder. The fold score cards are from 1949-1971, the day planners are from 1969-1979 and 1968-1987, and the letters from Julia to her mother are from 1933-1934.

The original letters can be found in `scans_original`. We processed these scans by rotating the pages to their correct orientation and fixed one naming mistakes.The processed, polished versions of the  scans can be found in the `processed_scans_pdf`folder.

Most of the documents are labeled "Year_Month_Day_Location.pdf" For example, a letter Julia wrote from Camp Mystic on August 3, 1927 and is named "1927-08-03_Mystic_CT.pdf". Some letters do not have known years, and thus the year is denoted as "19ND" in the file name.

There are a few exceptions to this standardized naming. Some telegrams include descriptions in their file name. For example, a valentine's day telegram is named "ND_Valentine_Greeting_by_Western_Union_from_Camp_Hulen_TX.pdf". Another is named "ND_Merry_Christmas_Telegram_from_Palacios_TX.pdf".

In order to extract text from the typed letters, we apply the tesseract R package to conduct optical character recognition (OCR). Tesseract is easily applied with image files, so we first convert the PDF files in the `processed_scans_pdf` to image files, and running tesseract on the image files. The text for each of the typed letters was extracted. The text files are located in the `transcriptions` folder. 
Future work will need to focus on manually transcribing the handwritten letters. Best practices for manual transcription are described in the `transcription_process` folder.

Lastly, a detailed report of this project and the content of the letters is in the `report` folder.


