# Brief Description:
File is corrupted haha
Upload to a hexeditor or use terminal commands to check the header of the file. Here are the magic numbers for a few common extensions
- JPEG/JFIF: FF D8 FF E0
- PNG: 89 50 4E 47
- PDF: 25 50 44 46
  As the clue mentions JPEG, we simply overwrite the first few bytes with the given magic number and save it as file.jpg (v imp dont just save without extension).
  We then get the desired flag: picoCTF(r3stor1ng_th3_by73s_249e4e3c)
