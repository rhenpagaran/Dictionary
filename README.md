# Dictionary

import collections
my_info = {1: {'Name':'Rhina G.Pagaran','Age':'20', 'Date of Birth':'June 25,1997',
              'Address':'27 Juliana Street Potrero Malabon City','Student No.':'2016-08971-MN-1',
              'Course': 'Bachelor of Science in Computer'},
          2: {'Name': 'Reah Mae G. Pagaran', 'Age':'17', 'Date of Birth':'December 25,1997',
              'Address': '27 Juliana Street Potrero Malabon City', 'LRN': '136848060277',
              'Track':'General Academic Strand'}}

for p_id, p_info in my_info.items():
    print("\nPerson ID:", p_id)
    
    for key in p_info:
        print(key + ':', p_info[key])       
