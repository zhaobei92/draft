draft
=====
#循环
def loop(dir):
  if os.path.isdir(dir):
            for files in os.path.listdir(dir):
                if files os.path.isdir(dir):
                    loop(files)
                else:
                	file=os.path.join(dir,files)
	else:
        file=dir
    return file
                
    	
        	dele(f)
def dele(f):
    f=file(f,'a+')
    data=f.readlines()
    count=0
    for  i in data:
draft
