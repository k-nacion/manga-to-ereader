# Manga to E-Reader Workflow Guide

This guide will walk you through the process of downloading manga and transferring it to your E-Reader device in a MOBI format. Below are the requirements, configurations, and detailed procedures to achieve this.

---

## Requirements

- **[Hakuneko](https://hakuneko.download/)**: For downloading manga chapters in CBZ format.
- **[CBZ Combiner](https://github.com/k-nacion/cbz-combiner)**: For combining multiple CBZ files into a single CBZ.
- **[KCC Plugin](https://github.com/ciromattia/kcc?tab=readme-ov-file#prerequisites)**: For converting CBZ files to MOBI format.
- **[Calibre](https://calibre-ebook.com/download)**: For uploading the MOBI files to your E-Reader device.

---

## Configurations

### Hakuneko Configuration

![Hakuneko Configuration](attachments/Hakuneko%20Configuration.png)

These settings in Hakuneko are optional, and you can configure them according to your preference.

However, **for CBZ Combiner to work**, ensure that the *Chapter File Format* is set to:  
**Comic Book Archive (*.cbz)**.

---

## Procedure

### 1. Downloading Manga with Hakuneko

1. **Visit a manga website** (e.g., [Mangadex](https://mangadex.org), [Mangafire](https://mangafire.to)). For this guide, we’ll use [Mangakatana](https://mangakatana.com) as an example.

2. **Select a manga** you want to download and copy its URL. Example: [Jigokuraku (KAKU Yuuji)](https://mangakatana.com/manga/jigokuraku-kaku-yuuji.19894).

3. Open **Hakuneko** and:
   - Select the source.  
     ![Hakuneko Source](attachments/Hakuneko%201.png)
   - Click the [Clipboard] as the source.  ![Hakuneko Clipboard](attachments/Hakuneko%202.png)
   - Press the refresh button to load the manga link.  ![Hakuneko Refresh](attachments/Hakuneko%203.png)

4. **Download chapters**:
   - Click the manga to load its chapters.
   - Use the download button to download all chapters, or select specific chapters by clicking the cloud icons.  ![Hakuneko Options](attachments/Hakuneko%204.png)
   - Optionally, bookmark the manga for easy access later.

All downloaded files will be saved to the directory configured in Hakuneko.

---

### 2. Combining CBZ Files

If you have multiple CBZ files and want to read seamlessly, use the **CBZ Combiner**.

1. Open **CBZ Combiner**.
2. Copy the directory containing the CBZ files for the manga.
3. Set the maximum output file size (recommended: 250 MB). This ensures compatibility with the KCC plugin, which cannot process files larger than ~300 MB.
4. The combiner will generate files in a new directory: `output/[manga_name]_[index].cbz`.
5. You now have combined CBZ files ready for conversion.

---

### 3. Converting CBZ to MOBI

**Note**: The configuration below is a suggestion. Feel free to adjust settings in the KCC plugin to suit your needs.

**Requirement**: Output file format must be MOBI or AZW3.

1. Open **KCC Plugin**.  
   ![KCC Plugin](attachments/KCC%201.png)

2. Drag and drop the combined CBZ files into the app.  
   ![Drag and Drop CBZ](attachments/KCC%202.png)

3. Click the **Convert** button to process the files.

4. Once conversion is complete, you will have MOBI files ready for uploading to your E-Reader.

---

### 4. Uploading MOBI Files to an E-Reader

1. Open **Calibre**.  
2. Drag and drop the MOBI files into Calibre.
3. Connect your E-Reader device via USB.  
   ![Connect Device](attachments/Calibre%201.png)

4. Highlight the books you want to send.
5. Click **Send to Device**.
6. Your manga is now available to read on your E-Reader!

---

## Additional Notes

- Ensure you follow the order of steps for successful file conversion and transfer.
- The screenshots are arranged sequentially to assist in each stage of the process.

