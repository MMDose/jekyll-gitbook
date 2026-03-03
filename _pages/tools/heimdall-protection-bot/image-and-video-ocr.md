# Image & Video OCR

***

### Image & Video Text Recognition (OCR) <a href="#ocr" id="ocr"></a>

Heimdall uses OCR to extract text from media sent in chat. This prevents scammers from bypassing text-based filters by putting their spam inside images or videos.

* **Image processing:** Images are converted to grayscale with automatic level and contrast enhancement for maximum OCR accuracy
* **Video processing:** Heimdall extracts the middle frame of a video (for best content representation) and runs OCR on it
* **Fallback logic:** If no text is found in the initial scan, additional frames are extracted and scanned
* **Spam checking:** All extracted text is combined with the message text and checked against the full spam detection ruleset

**Supported formats:** JPG, PNG, WebP, GIF, BMP, MP4, AVI, MKV, WebM, MOV, WMV, FLV, and more.
