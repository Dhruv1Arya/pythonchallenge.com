# pythonchallenge.com
My solutions to pythonchallenge.com

Challenge 0 : replace 0 with 2^38

Challenge 1 : replace the every alphabet in line with third alphabet in line. Use code:

              from string import ascii_lowercase as a
              b = a[2:] + a[0:2]
              table = str.maketrans(a, b)
              line = "g fmnc wms bgblr rpylqjyrc gr zw fylb. rfyrq ufyr amknsrcpq ypc dmp. bmgle gr gl zw fylb gq glcddgagclr ylb rfyr'q ufw rfgq rcvr gq qm jmle. sqgle qrpgle.kyicrpylq() gq pcamkkclbcb. lmu ynnjw ml rfc spj."
              print(line.translate(table))

              once you are done, read the text, its interesting. then change the **map** in url with **ocr**. hit enter

challenge 2: Go to page source. There will be a huge text of random characters. Copy them.

              a = copies_characters
              b = {}
              for i in a:
              if i not in b:
                b[i] = 0
              else:
                b[i] += 1
              print(b)
              
              look for the charcters that have 0 repetitions. They will be **equality**. replace **ocr** by **equality**.

challenger 3: http://www.pythonchallenge.com/pc/def/equality.html 
