# Exerc-cios
movies = ["The Holy Grail", 1975 , "Terry Jones & Terry Gilliam" , 91,
                         ["Graham Chapman", ["Michel Pallim", "Jhon Cleese",
                                             "Terry Gillam", "Eric Idle", "Terry Jones"]]]
def print_lol(movies):
     for each_item in movies:
          if isinstance(each_item, list):
               print_lol(each_item)
          else:
               print(each_item)
print_lol (movies)

#Estava usando esse aqui
#for each_item in movies:
  #if isinstance(each_item, list):
        #for nested_item in each_item:
      #if isinstnce(nested_item, list):
              #for deeper_item in nested_item:
          #if isinstance(deeper_item, list):
                  #for deepest_item in deeper_item:
                      #print(deepest_item)
          #else:
            print(deeper_item)
      #else:
        print(nested_item)
  #else:
    #print(each_item)    
#Ambos tem a mesma função, porém um é organizado o outro não.
