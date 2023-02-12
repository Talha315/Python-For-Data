# Python-For-Data
Having small codes related to fundamental concepts that must be known before entering into the programming world.



def mf(a,b):# defining funcyion that can multiply two list with each other using nested for loops
  for a in list1:
    for b in list2:
      c=a*b
      if c==20:
        continue
      elif c==18:
        break
      else:
        print(c)

if __name__=='__main__':

  list1=[2, 4, 6]
  list2=[1, 3, 5]
  mf(list1,list2)
