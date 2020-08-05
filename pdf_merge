from PyPDF2 import PdfFileMerger

#Write pdf file names
pdfs = ['1.pdf', '2.pdf', '3.pdf', '4.pdf', '5.pdf']

merger = PdfFileMerger()

for pdf in pdfs:
    merger.append(pdf)

#Write merged pdf file name
merger.write("result.pdf")
merger.close()
