# Manga to E-Reader Tutorial

This tutorial will guide you through the process of downloading manga and transferring it to your e-reader device. Screenshots are included to help illustrate each step.

---

## Requirements

- [Hakuneko](https://hakuneko.download/) — for downloading manga chapters in CBZ format.
- [CBZ Combiner](https://github.com/k-nacion/cbz-combiner) — for combining multiple CBZ files.
- [KCC Plugin](https://github.com/ciromattia/kcc?tab=readme-ov-file#prerequisites) — for converting CBZ files to MOBI format.
- [Calibre](https://calibre-ebook.com/download) — for uploading MOBI files to your e-reader device.

---

## Configurations

### Hakuneko

![Hakuneko Configuration](attachments/Hakuneko%20Configuration.png)

These settings in Hakuneko are all **optional**. You can configure your own settings. **However**, for CBZ Combiner to work, the *Chapter File Format* must be set to *Comic Book Archive (*.cbz)*.

---

## Procedure

### 1. Downloading Manga from Hakuneko
1. Go to your manga website of choice (e.g., mangadex.org, mangafire.to). For this tutorial, we'll use Mangakatana.com.
2. Find a manga you want to download. For example: [Jigokuraku (KAKU Yuuji)](https://mangakatana.com/manga/jigokuraku-kaku-yuuji.19894). Copy the URL of the manga.
3. Open Hakuneko.
4. Click the **Clipboard** option as shown below:

   ![Hakuneko 1](attachments/Hakuneko%201.png)

5. Press the refresh button to load the link from the clipboard:

   ![Hakuneko 2](attachments/Hakuneko%202.png)

6. Download the manga chapters by following these steps:
   - Click the manga to load the chapters in the right pane.
   - Use the **Download** button to save all chapters or download specific chapters using the cloud icon.
   - Bookmark the manga for easy access later.

   ![Hakuneko 3](attachments/Hakuneko%203.png)

   ![Hakuneko 4](attachments/Hakuneko%204.png)

   All downloaded files will be saved in your configured directory.

---

### 2. Combining the CBZ Files

If the manga chapters are saved as multiple CBZ files, use CBZ Combiner to merge them.

1. Open CBZ Combiner.
2. Copy the directory containing the CBZ files.
3. Set the maximum file size (recommended: 250 MB to ensure compatibility with KCC).
4. The combined CBZ files will be generated in the **output/** directory.

---

### 3. Converting CBZ to MOBI

To convert CBZ files to MOBI for e-readers:

1. Open KCC.

   ![KCC 1](attachments/KCC%201.png)

2. Drag and drop the combined CBZ files into KCC.

   ![KCC 2](attachments/KCC%202.png)

3. Press the **Convert** button. Once completed, the MOBI files will be ready.

---

### 4. Uploading MOBI to Your E-Reader

1. Open Calibre.

   ![Calibre 1](attachments/Calibre%201.png)

2. Drag and drop the MOBI files into Calibre.
3. Connect your e-reader device via USB.
4. Highlight the books to transfer and click **Send to device**.
5. Enjoy reading manga on your e-reader!

---

## Notes
- Ensure the CBZ file sizes do not exceed ~300 MB for compatibility with KCC.
- Adjust configurations based on your preferences.

---

For any issues or suggestions, feel free to create an issue in this repository!

All the downloaded files are stored in the directory where you configured this. 

### Combining the CBZ files
As you can see, there is a lot of CBZ files that was generated. And if you want to combine them for reading seamlessly, we can combine this with CBZ Combiner. 

1. Open the CBZ Combiner. 
2. Copy the directory of the manga that contains the CBZ files.
3. CBZ Combiner will ask for the maximum file size to be generated.
   Why? because the KCC plugin is only capable of maximum ~300 mb and cannot process more than that. I usually go for 250 MB limit.  
4. This will generate a directory relative to the CBZ Combiner current directory. It will generate **output/[manga_name]_[index].cbz**. depending on how many output files will be generated. 
5. Now that you have a combined CBZ files, we can proceed to convert the CBZ file to MOBI format. 

### Converting CBZ to MOBI
Note: the configuration are just a suggestion for the KCC. You can absolutely modify the configurations that was set here to your liking. 

**Requirement**:
- File format must be a MOBI./AZW3 to produce a MOBI format. 

1. Open up the KCC plugin. 
   ![[KCC 1.png]]
2. Drag and drop the CBZ files that was generated to this KCC app. 
   ![[KCC 2.png]]
3. Press the **Convert** button. 
4. Once completed, we can upload these MOBI generated file to your E-Reader device. 

### Uploading MOBI to E-Reader device. 
1. Open up Calibre.
2. Drag and drop the MOBI files to the Calibre app. 
3. Connect your E-Reader device to your computer via USB. 
![[Calibre 1.png]]
4. Highlight the books that you wanted to send. 
5. Press the "Send to device". 
6. That's it! You can now read the books/manga in your E-reader device. 