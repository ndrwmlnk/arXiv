# arXiv how to  
**1. Download the Overleaf Project:**  
   In Overleaf, go to Submit → Download Project ZIP with submission files (e.g. .bbl)  

**2.	Clean Up the LaTeX Files:**  
   Use the tool [arxiv-latex-cleaner](https://github.com/google-research/arxiv-latex-cleaner) to automatically remove unused files and commented-out sections from your .tex files. Otherwise, comments left in .tex files and unused images remain visible on arXiv under **Access Paper: TeX Source**. Do not rely on automatic image size reduction with [arxiv-latex-cleaner](https://github.com/google-research/arxiv-latex-cleaner); it’s better to reduce image size manually on a case-by-case basis.  

**3.	Check the PDF File Size:**  
Download the PDF from Overleaf and check its size. As a rule of thumb, one graphics-heavy page should be under 1 MB.  
For example for a PDF paper with 7 figures:  
	•	5 half-page figures → ~2.5 MB  
	•	2 full-page figures → ~2 MB  
	•	Text content → ~0.5 MB  
	•	Total PDF size: Should be under ~5 MB  

**4. If your PDF exceeds this:**  
inspect the figures and identify which ones are too large. Back up original files and try the following to reduce size:  
	•	Convert to more efficient formats (e.g., JPG, PNG, PDF)  
	•	For figures that consist mainly of text, bounding boxes, and arrows, save them as PDFs directly from the editor where the content is editable (e.g., https://miro.com). This will result in a much smaller file—comparable in size to a text document with the same word count.  
	•	Reduce JPG quality (Tip: For a given file size, it’s generally better to use a higher resolution with lower quality than a lower resolution with higher quality)  
	•	Apply multi-step compression to PNGs. [How to Compress PNG Images Without Losing Quality](https://shortpixel.com/blog/compress-png-images-without-losing-quality)  
 	•	Resize images  

**5. Inspect the final quality of figures in PDF:**  
   •	text should be sharp and readable  
   •	all tiny details remain visible  

**6. Upload the lightweight, cleaned project to arXiv:**  
•	Refer to the [Announcement Schedule](https://info.arxiv.org/help/availability.html) to see when your submission will appear publicly and receive its final arXiv URL.  
•	Share the arXiv URL and the paper password (emailed to the submitting author) with co-authors.  
