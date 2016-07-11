def csv_writer(uygulayici, patient_ID, patient_age, patient_sex, patient_edu, test_name, printable_list):
    import csv
    from time import strftime
    date = strftime("%Y-%m-%d")
    time = strftime("%H:%M:%S")
    with open(test_name, 'a', encoding='ISO-8859-9', newline='') as csvfile:
        data_writer = csv.writer(csvfile, delimiter=',', quotechar='|', quoting=csv.QUOTE_MINIMAL)
        data = ["", uygulayici, date, time, patient_ID, patient_age, patient_sex, patient_edu] + printable_list
        data_writer.writerow(data)
        csvfile.close()

def txt_writer(uygulayici, patient_ID, console_results):
    from time import strftime
    date = strftime("%Y-%m-%d")
    file_name = str(patient_ID) + "-(" + date + ")-" + uygulayici + ".txt"
    with open(file_name, 'a', encoding='UTF-8') as file:
        file.write("\n" + console_results)
        file.close()

def txt_writer_create(uygulayici, patient_ID, patient_age, patient_sex, patient_edu):
    from time import strftime
    date = strftime("%Y-%m-%d")
    time = strftime("%H:%M:%S")
    file_name = str(patient_ID) + "-(" + date + ")-" + uygulayici + ".txt"
    patient_name = input("Hastanın ismi: ")
    with open(file_name, 'w', encoding='UTF-8') as file:
        file.write("Testi uygulayan: " + uygulayici + "\nGünün tarihi: " + date + "\nSaat: " + time +
        "\nHastanın ismi: " +  patient_name + "\nHastanın kodu: " + str(patient_ID) +
        "\nHastanın yaşı: " + str(patient_age) + "\nHastanın cinsiyeti: " + str(patient_sex) +
        "\nHastanın toplam eğitim yılı: " + str(patient_edu) +
        "\n=============================================\n")
        file.close()

def patient_age_func():
#Loop düzgün giriş yapılana kadar dönüyor
#Doğru giriş yapılırsa "break" ve istenilen değeri geri veriyor
    while True:   
        try:        
            patient_age = int(input("Hastanın yaşı: "))
        except:            
            print("Lütfen sadece rakam giriniz.")
            continue
        else:
            break
    return patient_age
    
def patient_sex_func():   
#Loop düzgün giriş yapılana kadar dönüyor
#Doğru giriş yapılırsa "break" ve istenilen değeri geri veriyor
    while True:    
        patient_sex_user_input = input("Hastanın cinsiyeti: (1) Kadın - (2) Erkek: ")
        if patient_sex_user_input == "1":
            patient_sex = "Kadın"
            break
        elif patient_sex_user_input == "2":
            patient_sex = "Erkek"
            break
        else:
            print("Lütfen sadece 1 veya 2 giriniz.")
            continue
    return patient_sex
        
def patient_edu_func(): 
#Loop düzgün giriş yapılana kadar dönüyor
#Doğru giriş yapılırsa "break" ve istenilen değeri geri veriyor
    while True:
        try:
            patient_edu = int(input("Hastanın toplam eğitim yılı: "))
        except:
            print("Lütfen sadece rakam giriniz.")
            continue
        else:
            break
    return patient_edu


def menu(patient_ID, patient_age, patient_edu, patient_sex, uygulayici, menu_done_tests):
    try:
        menu_list = [stroop, verbal_fluency, sem_flu, sbst, trail_making,
                     mmt, clock_drawing, moca, ipucu, wisconsin, wechsler, rkft, sdot]   #testlerin fonksiyon isimleri
        
        test_name_list = ["(1)Stroop ", "(2)Sözel akıcılık ", "(3)Semantik Akıcılık ",
                          "(4)SBST ", "(5)İz sürme ", "(6)Mini Mental test ", "(7)Saat çizme ",
                          "(8)MOCA ", "(9)Artırılmış İpuçlu Hatırlama ", 
                          "(10)Yetişkin Wisconsin Kart Eşleme ", "(11)Wechsler Zeka testi ",
                          "(12)Rey Karmaşık Figür Testi ", "(13)Çizgi yönünü belirleme testi "] #testlerin kullanıcı isimleri
        
        menu_ui = ("==================================================\n") #menüyü hazırlıyor
        for i in range(len(test_name_list)):
            if (i+1)%3 == 0:
                menu_ui = menu_ui + test_name_list[i] + "\n"
            else:
                menu_ui = menu_ui + test_name_list[i]
                
        menu_ui = menu_ui + "\n"
        
        print(menu_ui)
        print("Şu ana kadar yapılan testler: ")
        print(menu_done_tests)
        menu_input = int(input("Girmek istediğiniz testin numarasını giriniz veya çıkış için (" + str(len(menu_list)+1) + ") giriniz: " ))        
        
        if menu_input in menu_done_tests:
            x = input("Bu test zaten girilmiş, tekrar girmek istiyor musunuz? (e)vet/(h)ayır: ")
            if x == "E" or x == "e":
                print("Bu test daha öncesinde yapıldığı için, veri bankasında birden fazla girişe" +
                " neden olacaktır, lütfen sonrasında düzeltmeyi unutmayınız.")
            else:
                print("Bir önceki basamağa geri dönülüyor.")
                menu(patient_ID, patient_age, patient_edu, patient_sex, uygulayici, menu_done_tests)

        if menu_input <= len(menu_list):
            menu_done_tests.append(test_name_list[menu_input-1])
            menu_list[menu_input-1](patient_ID, patient_age, patient_edu, patient_sex, uygulayici)
            menu(patient_ID, patient_age, patient_edu, patient_sex, uygulayici, menu_done_tests)
            
        elif menu_input == (len(menu_list)+1):
            print("\nİşlem iptal edildi, şu ana kadar yapılanlar kaydedildi. " +
            "Program baştan başlatılıyor.")
            startup()
            
        elif (len(menu_list)+1) < menu_input:
            print("\nLütfen listede olan numaralardan giriniz.")
            menu(patient_ID, patient_age, patient_edu, patient_sex, uygulayici, menu_done_tests)
    except:
        print("\n Lütfen sadece rakam giriniz.")
        menu(patient_ID, patient_age, patient_edu, patient_sex, uygulayici, menu_done_tests)

def startup(): #Kullanıcıyı karşılayacak program
    print("\n===========================================\n" + 
    "Akbulut Standart Sapma Hesaplayıcı v0.4.1" +
    "\n===========================================\n")    

    uygulayici = input("Testi uygulayan kişi: ")    
    patient_ID = input("Hastanın kodu: ")
    patient_age = patient_age_func()
    patient_sex = patient_sex_func()
    patient_edu = patient_edu_func()
    menu_done_tests = []
    
    print("=======================================")    
    user_input = input("Yukarıdaki bilgileri onaylıyor musunuz? (e)vet/(h)ayır: ")
    if user_input == "E" or user_input == "e":
        txt_writer_create(uygulayici, patient_ID, patient_age, patient_sex, patient_edu)
        menu(patient_ID, patient_age, patient_edu, patient_sex, uygulayici, menu_done_tests)
    else:
        print("Program tekrar başlatılıyor.")
        startup()

def std_dev_int_calc(result_list, mean_list, sd_list): #hastanın hangi SD aralığında olduğunu bulup listeliyor
    std_dev_output_list = []
    for i in range(len(result_list)):
        std_dev_output_list.append(float("%.2f" % std_dev_calc(result_list[i], mean_list[i], sd_list[i])))
    return std_dev_output_list

def printable_list_maker(result_list, std_dev_output_list, std_dev_verbal_list):
             #listeleri toparlayıp, csv için minimalist hale getiriyor
                        #sırasını da düzenliyor
    printable_list = []
    for y in range(len(result_list)):
        printable_list.append(result_list[y])
        printable_list.append(std_dev_output_list[y])
        printable_list.append(std_dev_verbal_list[y])
    return printable_list

def console_result_feedback(result_list, std_dev_output_list, std_dev_verbal_list):
    #konsoldan canlı feedback için data hazırlıyor
    console_result = []
    for i in range(len(std_dev_output_list)):
        console_result.append("Hastanın puanı: " + str(result_list[i]) + ", " + 
        str(std_dev_verbal_list[i]) + ", " + str(std_dev_output_list[i]) + "SD")
    return console_result

    
def std_dev_calc(user_input, mean, std_dev):
    #std_dev = hastanın mean'den kaç ortalama sapma uzak olduğu
    #(Hastanın süresi - mean) / standart sapma
    return ((user_input - mean) / std_dev)

def less_std_dev_better(std_dev_float): #SD'lerden verbal sonuç hesaplıyor
    normal = "Normal."
    hafif = "Hafif bozulma."
    orta = "Orta derecede bozulma."
    agir = "Ağır bozulma."
    if std_dev_float <= 1:
        return normal
    elif std_dev_float > 1 and std_dev_float <= 2:
        return hafif
    elif std_dev_float > 2 and std_dev_float <= 3:
        return orta
    else:
        return agir    

def more_std_dev_better(std_dev_float):
    normal = "Normal."
    hafif = "Hafif bozulma."
    orta = "Orta derecede bozulma."
    agir = "Ağır bozulma."
    if std_dev_float >= -1:
        return normal
    elif -2 <= std_dev_float < -1:
        return hafif
    elif -3 <= std_dev_float < -2:
        return orta
    else:
        return agir 

def which_sd_better_list(std_dev_output_list, which_better): #verbal sonuçları listeye çeviriyor
    std_dev_verbal_list = []
    for x in range(len(std_dev_output_list)):
        std_dev_verbal_list.append(which_better(std_dev_output_list[x]))
    return std_dev_verbal_list
    
def wechsler(patient_ID, patient_age, patient_edu, patient_sex, uygulayici):
    try:
        try:        
            print("\n===================================\nWechsler zeka testi: \n")
            wech_1 = int(input("Genel bilgi: "))
            wech_2 = int(input("Yargılama: "))
            wech_3 = int(input("Aritmetik: "))
            wech_4 = int(input("Benzerlik: "))
            wech_5 = int(input("Sayı dizisi: "))
            wech_6 = int(input("Kelime: "))
            wech_7 = int(input("Şifre: "))
            wech_8 = int(input("Resim tamamlama: "))
            wech_9 = int(input("Küplerle desen: "))
            wech_10 = int(input("Resim düzenleme: "))
            wech_11 = int(input("Parça birleştirme: "))

            
            result_list = [wech_1, wech_2, wech_3, wech_4, wech_5, wech_6, wech_7,
            wech_8, wech_9, wech_10, wech_11]
                
            result_name = ["\nGenel bilgi: ", "\nYargılama: ", "\nAritmetik: ", "\nBenzerlik: ",
                           "\nSayı dizisi: ", "\nKelime: ", "\nŞifre: ", "\nResim tamamlama: ",
                           "\nKüplerle desen: ", "\nResim düzenleme: ", "\nParça birleştirme: "]    
             
            norm_exists = True
        except:
            print("Lütfen sadece rakam giriniz.")
            wechsler(patient_ID, patient_age, patient_edu, patient_sex, uygulayici)        

#Bütün SD'lerin üst sınır değerleri burada sıralı wech_1'den wech_11'e
        wech_m2_list = [4, 6, 4, 3, 7, 11, 18, 4, 10, 8, 11]
        wech_m1_list = [9, 12, 7, 7, 9, 22, 35, 8, 21, 15, 22] 
        wech_0_list = [15.5, 17.5, 11, 13.5, 11, 43, 54.5, 14, 32.5, 24, 32]
        wech_1_list = [23, 22, 15, 21, 14, 63, 69, 19, 44, 32, 40]
        wech_2_list = [27, 25, 18, 24, 17, 74, 79, 21, 48, 35, 43]
        
        std_dev_verbal_list = []          
        
        sd_m2 = "-2SD'den küçük, ağır bozulma"
        sd_m1 = "-1SD ve -2SD aralığında, hafif bozulma"
        sd_m0 = "0SD ve -1SD aralığında, normal"
        sd_0 = "0SD ve 1SD aralığında, normal"
        sd_1 = "1SD ve 2SD aralığında, normal"
        sd_2 = "2SD üzerisinde, normal"
        
#Girilen sonuçlar hangi SD aralığında diye sırayla deniyor tüm aralıkları
        for i in range(len(result_list)):
            if result_list[i] < wech_m2_list[i]:
                std_dev_verbal_list.append(sd_m2)
            elif wech_m2_list[i] <= result_list[i] < wech_m1_list[i]:
                std_dev_verbal_list.append(sd_m1)
            elif wech_m1_list[i] <= result_list[i] < wech_0_list[i]:
                std_dev_verbal_list.append(sd_m0)
            elif wech_0_list[i] <= result_list[i] < wech_1_list[i]:
                std_dev_verbal_list.append(sd_0)
            elif wech_1_list[i] <= result_list[i] < wech_2_list[i]:
                std_dev_verbal_list.append(sd_1)
            elif wech_2_list[i] <= result_list[i]:
                std_dev_verbal_list.append(sd_2)
                
                
        printable_list = []
        for y in range(len(result_list)):
            printable_list.append(result_list[y])
            printable_list.append(std_dev_verbal_list[y])

        test_name = 'wechsler_data.csv' #test datasının toplanacağı csv dosyasını belirtiyor
        csv_writer(uygulayici, patient_ID, patient_age, patient_sex, patient_edu, test_name, printable_list)
        
        
        console_result_feedback = []
        for i in range(len(result_list)):
            console_result_feedback.append("Hastanın puanı: " + str(result_list[i]) + ", " + str(std_dev_verbal_list[i]))
          
        console_results = "\n===================================\nWechsler zeka testinin sonuçları: "
        
        for i in range(len(result_list)):
            console_results = console_results + (result_name[i] + str(console_result_feedback[i]))    
            
        console_results = console_results + ("\n===================================\n")
        
        
        if norm_exists:
            txt_writer(uygulayici, patient_ID, console_results)
            print(console_results)
        else:
            txt_writer(uygulayici, patient_ID, ("Wechsler: Bu grup için norm mevcut değildir.\n" + console_results))
            return
        
    except:
        print("Wechsler zeka testini değerlendirirken bir hata oluştu, program kapatılacak.")
        raise
        return
        

def sem_flu(patient_ID, patient_age, patient_edu, patient_sex, uygulayici):
    try:
        try:        
            print("\n===================================\nSemantik akıcılık: \n")
            sf_name = float(input("Semantik akıcılık, Hayvan: "))
            sf_animal = float(input("Semantik akıcılık, İnsan: "))
            sf_alternate = float(input("Semantik akıcılık, İnsan-Hayvan: "))
            result_list = [sf_name, sf_animal, sf_alternate]

            result_name = ["\nHayvan için: ", "\nİnsan için: ", "\nİnsan-Hayvan için: "]    
             
            mean_list = []
            sd_list = []
            for i in range(len(result_list)):
                mean_list.append(result_list[i]-999)
                sd_list.append(1) 
 
            norm_exists = True
        except:
            print("Lütfen sadece rakam giriniz.")
            sem_flu(patient_ID, patient_age, patient_edu, patient_sex, uygulayici)

        if patient_sex == "Kadın": 
            if 5 <= patient_edu <= 8:
                if 15 <= patient_age <= 24:
                    mean_list = [14.20, 22.30, 16.50] #Hayvan, İnsan, Hayvan-insan için ortalamalar sıralı liste
                    sd_list = [3.82, 5.21, 3.17] #Hayvan, İnsan, Hayvan-insan için standart sapma sıralı liste        
                    
                elif 25 <= patient_age <= 34:
                    mean_list = [15.40, 24.30, 16.30]
                    sd_list = [3.13, 6.67, 3.16]
        
                elif 35 <= patient_age <= 44:
                    mean_list = [16.83, 25.42, 16.83]
                    sd_list = [3.27, 4.32, 4.00]
        
                elif 45 <= patient_age <= 54:
                    mean_list = [16.83, 25.92, 17.50]
                    sd_list = [3.19, 5.16, 4.70]
        
                elif 55 <= patient_age <= 64:
                    mean_list = [16.91, 22.09, 14.10]
                    sd_list = [5.63, 5.05, 4.32]
                
                elif 65 <= patient_age:
                    mean_list = [17.36, 21.91, 14.91]
                    sd_list = [2.50, 6.27, 4.41]
                else:
                    print("Bu yaş grubu için norm mevcut değildir.")
                    norm_exists = False
                    
            elif 9 <= patient_edu <= 11:
                if 15 <= patient_age <= 24:
                    mean_list = [21.70, 32.70, 21.60]
                    sd_list = [4.92, 5.88, 4.40]  
                    
                elif 25 <= patient_age <= 34:
                    mean_list = [29.64, 20.45, 21.45]
                    sd_list = [4.80, 7.10, 7.27]
        
                elif 35 <= patient_age <= 44:
                    mean_list = [20.00, 27.50, 19.20]
                    sd_list = [3.92, 5.15, 3.36]
        
                elif 45 <= patient_age <= 54:
                    mean_list = [20.10, 27.00, 20.10]
                    sd_list = [4.43, 6.16, 5.11]
        
                elif 55 <= patient_age <= 64:
                    mean_list = [21.83, 29.83, 20.33]
                    sd_list = [6.28, 9.81, 6.44]
                
                elif 65 <= patient_age:
                    mean_list = [17.90, 23.22, 15.44]
                    sd_list = [4.57, 7.69, 4.82]
                else:
                    print("Bu yaş grubu için norm mevcut değildir.")
                    norm_exists = False
                    
            elif 12 <= patient_edu:
                if 15 <= patient_age <= 24:
                    mean_list = [21.82, 28.63, 21.27]
                    sd_list = [3.90, 5.20, 3.10]  
                    
                elif 25 <= patient_age <= 34:
                    mean_list = [21.50, 32.83, 21.83]
                    sd_list = [4.68, 8.10, 3.41]
        
                elif 35 <= patient_age <= 44:
                    mean_list = [24.00, 31.21, 22.43]
                    sd_list = [4.24, 5.49, 5.15]
        
                elif 45 <= patient_age <= 54:
                    mean_list = [21.90, 30.50, 19.80]
                    sd_list = [3.80, 8.20, 5.92]
        
                elif 55 <= patient_age <= 64:
                    mean_list = [21.82, 27.82, 19.18]
                    sd_list = [5.55, 6.42, 4.02]
                
                elif 65 <= patient_age:
                    mean_list = [21.30, 27.80, 20.40]
                    sd_list = [8.00, 9.85, 5.15]
                else:
                    print("Bu yaş grubu için norm mevcut değildir.")
                    norm_exists = False
            else:
                print("Bu eğitim grubu için norm mevcut değildir.")
                norm_exists = False
                
        elif patient_sex == "Erkek": 
            if 5 <= patient_edu <= 8:
                if 15 <= patient_age <= 24:
                    mean_list = [17.20, 24.60, 18.60]
                    sd_list = [2.49, 3.34, 1.65]
                    
                elif 25 <= patient_age <= 34:
                    mean_list = [19.18, 24.18, 18.27]
                    sd_list = [5.53, 6.24, 4.08]
        
                elif 35 <= patient_age <= 44:
                    mean_list = [17.00, 23.30, 17.80]
                    sd_list = [4.62, 6.46, 2.97]
        
                elif 45 <= patient_age <= 54:
                    mean_list = [18.60, 22.70, 17.70]
                    sd_list = [3.10, 5.21, 3.10]
        
                elif 55 <= patient_age <= 64:
                    mean_list = [15.10, 19.80, 13.30]
                    sd_list = [5.76, 5.88, 4.55]
                
                elif 65 <= patient_age:
                    mean_list = [16.50, 17.10, 13.20]
                    sd_list = [5.30, 5.11, 3.12]
                else:
                    print("Bu yaş grubu için norm mevcut değildir.")
                    norm_exists = False
                    
            elif 9 <= patient_edu <= 11:
                if 15 <= patient_age <= 24:
                    mean_list = [19.85, 28.46, 20.92]
                    sd_list = [6.04, 8.55, 3.62]  
                    
                elif 25 <= patient_age <= 34:
                    mean_list = [21.82, 28.00, 20.36]
                    sd_list = [4.77, 5.80, 4.37]
        
                elif 35 <= patient_age <= 44:
                    mean_list = [20.30, 27.10, 18.50]
                    sd_list = [5.25, 4.33, 4.22]
        
                elif 45 <= patient_age <= 54:
                    mean_list = [21.10, 23.27, 17.64]
                    sd_list = [4.44, 3.82, 3.35]
        
                elif 55 <= patient_age <= 64:
                    mean_list = [18.45, 22.55, 18.36]
                    sd_list = [4.61, 6.74, 4.95]
                
                elif 65 <= patient_age:
                    mean_list = [16.80, 19.40, 15.80]
                    sd_list = [4.66, 3.20, 2.62]
                else:
                    print("Bu yaş grubu için norm mevcut değildir.")
                    norm_exists = False
            
            elif 12 <= patient_edu:
                if 15 <= patient_age <= 24:
                    mean_list = [23.04, 31.91, 23.35]
                    sd_list = [3.62, 7.60, 5.79]
                    
                elif 25 <= patient_age <= 34:
                    mean_list = [20.79, 27.50, 20.57]
                    sd_list = [3.29, 6.47, 4.52]
        
                elif 35 <= patient_age <= 44:
                    mean_list = [20.40, 26.20, 20.70]
                    sd_list = [3.89, 4.44, 3.34]
        
                elif 45 <= patient_age <= 54:
                    mean_list = [21.30, 26.57, 21.86]
                    sd_list = [7.10, 6.81, 5.05]
        
                elif 55 <= patient_age <= 64:
                    mean_list = [20.60, 24.10, 17.80]
                    sd_list = [3.31, 3.90, 2.49]
                
                elif 65 <= patient_age:
                    mean_list = [19.60, 21.90, 15.80]
                    sd_list = [4.97, 8.54, 5.31]
                else:
                    print("Bu yaş grubu için norm mevcut değildir.")
                    norm_exists = False
            
            else:
                print ("Bu eğitim grubu için norm mevcut değildir.")
                norm_exists = False
        else:
            print("Bu cinsiyet için norm mevcut değildir.")
            norm_exists = False
        
        std_dev_output_list = std_dev_int_calc(result_list, mean_list, sd_list)
        std_dev_verbal_list = which_sd_better_list(std_dev_output_list, more_std_dev_better)
        printable_list = printable_list_maker(result_list, std_dev_output_list, std_dev_verbal_list)

        test_name = 'semantic_fluency_data.csv' #test datasının toplanacağı csv dosyasını belirtiyor
        csv_writer(uygulayici, patient_ID, patient_age, patient_sex, patient_edu, test_name, printable_list)
        
                  
        console_results = "\n===================================\nSemantik akıcılık testinin sonuçları: "
        for i in range(len(mean_list)):
            console_results = console_results + (result_name[i] + str(console_result_feedback(result_list, std_dev_output_list, std_dev_verbal_list)[i]))            
        console_results = console_results + ("\n===================================\n")
        
        
        if norm_exists:
            txt_writer(uygulayici, patient_ID, console_results)
            print(console_results)
        else:
            txt_writer(uygulayici, patient_ID, ("Semantik akıcılık: Bu grup için norm mevcut değildir.\n" + console_results))
            return
        
    except:
        print("Semantik akıcılık testini değerlendirirken bir hata oluştu, program kapatılacak.")
        raise
        return
        
def mmt(patient_ID, patient_age, patient_edu, patient_sex, uygulayici):
    try:
        score = int(input("\nMini mental test puanı: "))
        result_name = "MMT test: "
        if patient_edu < 5:
            if score < 18:
                verbal_result = ", Bozuk"
                console_results =  (result_name + str(score) + verbal_result)             
            elif 18 <= score <= 19:
                verbal_result = ", Sınır değer"
                console_results = (result_name + str(score) + verbal_result)
            elif 19 < score:
                verbal_result = ", Normal"
                console_results = (result_name + str(score) + verbal_result)
                
        elif 5 <= patient_edu:
            if score < 22:
                verbal_result =  ", Bozuk"
                console_results =  (result_name + str(score) + verbal_result)
            elif 22 <= score <= 23:
                verbal_result =  ", Sınır değer"
                console_results = (result_name + str(score) + verbal_result)
            elif 23 < score:
                verbal_result = ", Normal"
                console_results = (result_name + str(score) + verbal_result)
                
        printable_list = [score, verbal_result]
        
        console_results = console_results + "\n==================================\n"
        test_name = 'MMT.csv' #test datasının toplanacağı csv dosyasını belirtiyor
        csv_writer(uygulayici, patient_ID, patient_age, patient_sex, patient_edu, test_name, printable_list)
        txt_writer(uygulayici, patient_ID, console_results)
        print(console_results)        
    except:
        print("Lütfen yalnızca rakam giriniz")
        mmt(patient_ID, patient_age, patient_edu, patient_sex, uygulayici)

def ipucu(patient_ID, patient_age, patient_edu, patient_sex, uygulayici):
    try:
        score = int(input("\nArtırılmış ipuçlu hatırlama: "))
        result_name = "Artırılmış ipuçlu hatırlama: "
        if score < 41:
            verbal_result = ", Bozuk"
            console_results =  (result_name + str(score) + verbal_result)
        elif 41 <= score <= 42:
            verbal_result = ", Sınır değer"
            console_results = (result_name + str(score) + verbal_result)
        elif 42 < score:
            verbal_result = ", Normal"
            console_results = (result_name + str(score) + verbal_result)
                
        printable_list = [score, verbal_result]
        
        console_results = console_results + "\n==================================\n"
        test_name = 'ipucu.csv' #test datasının toplanacağı csv dosyasını belirtiyor
        csv_writer(uygulayici, patient_ID, patient_age, patient_sex, patient_edu, test_name, printable_list)
        txt_writer(uygulayici, patient_ID, console_results)
        print(console_results)        
    except:
        print("Lütfen yalnızca rakam giriniz")
        ipucu(patient_ID, patient_age, patient_edu, patient_sex, uygulayici)
                
def moca(patient_ID, patient_age, patient_edu, patient_sex, uygulayici):
    try:
        score = int(input("\nMOCA: "))
        result_name = "MOCA: "
        if score < 21:
            verbal_result = ", Bozuk"
            console_results = (result_name + str(score) + verbal_result)
        elif 21 <= score:
            verbal_result = ", Normal"
            console_results = (result_name + str(score) + verbal_result)
                
        printable_list = [score, verbal_result]
        
        console_results = console_results + "\n==================================\n"
        test_name = 'moca.csv' #test datasının toplanacağı csv dosyasını belirtiyor
        csv_writer(uygulayici, patient_ID, patient_age, patient_sex, patient_edu, test_name, printable_list)
        txt_writer(uygulayici, patient_ID, console_results)
        print(console_results)        
    except:
        print("Lütfen yalnızca rakam giriniz")
        moca(patient_ID, patient_age, patient_edu, patient_sex, uygulayici)
        
def clock_drawing(patient_ID, patient_age, patient_edu, patient_sex, uygulayici):
    try:
        score = int(input("\nSaat çizme: "))
        result_name = "Saat çizme: "
        if score < 3:
            verbal_result = ", Bozuk"
            console_results = (result_name + str(score) + verbal_result)
        elif 3 <= score:
            verbal_result = ", Normal"
            console_results = (result_name + str(score) + verbal_result)
                
        printable_list = [score, verbal_result]
        
        console_results = console_results + "\n==================================\n"
        test_name = 'clock.csv' #test datasının toplanacağı csv dosyasını belirtiyor
        csv_writer(uygulayici, patient_ID, patient_age, patient_sex, patient_edu, test_name, printable_list)
        txt_writer(uygulayici, patient_ID, console_results)
        print(console_results)        
    except:
        print("Lütfen yalnızca rakam giriniz")
        clock_drawing(patient_ID, patient_age, patient_edu, patient_sex, uygulayici)

   
def verbal_fluency(patient_ID, patient_age, patient_edu, patient_sex, uygulayici):
    try:
        try:
            print("\n===================================\nSözel akıcılık: \n")
            vf_s = float(input("'S' harfi için: "))
            vf_a = float(input("'A' harfi için: "))
            vf_z = float(input("'Z' harfi için: "))
            result_list = [vf_s, vf_a, vf_z]        
            
            result_name = ["\n'S' harfi için: " , "\n'A' harfi için: ", "\n'Z' harfi için: "]               
            mean_list = []
            sd_list = []
            for i in range(len(result_list)):
                mean_list.append(result_list[i]-999)
                sd_list.append(1)      
    
            norm_exists = True
        except:
            print("Lütfen sadece rakam giriniz.")
            verbal_fluency(patient_ID, patient_age, patient_edu, patient_sex, uygulayici)
            
        if 5 <= patient_edu <= 8:
            if 15 <= patient_age <= 24:
                mean_list = [7, 6.45, 4.25] #[S, A, Z] için ortalamalar sıralı liste
                sd_list = [3.49, 3.15, 2.24] #[S, A, Z] için standart sapma sıralı liste        
                
            elif 25 <= patient_age <= 34:
                mean_list = [6.81, 6.38, 4.00]
                sd_list = [4.15, 2.48, 2.45]
    
            elif 35 <= patient_age <= 44:
                mean_list = [8.73, 7.23, 4.95]
                sd_list = [5.37, 4.12, 2.36]
    
            elif 45 <= patient_age <= 54:
                mean_list = [7.73, 7.05, 6.23]
                sd_list = [2.95, 3.08, 2.51]
    
            elif 55 <= patient_age <= 64:
                mean_list = [7.71, 6.29, 5.24]
                sd_list = [3.72, 3.02, 2.53]
            
            elif 65 <= patient_age:
                mean_list = [8.95, 7.00, 6.19]
                sd_list = [3.58, 4.07, 2.82]
            else:
                print("Bu yaş grubu için norm mevcut değildir.")
                norm_exists = False
                
        elif 9 <= patient_edu <= 11:
            if 15 <= patient_age <= 24:
                mean_list = [11.13, 11.43, 6.04]
                sd_list = [3.45, 5.77, 3.08]        
                
            elif 25 <= patient_age <= 34:
                mean_list = [11.45, 9.55, 7.73]
                sd_list = [4.94, 3.76, 3.21]
    
            elif 35 <= patient_age <= 44:
                mean_list = [11.50, 11.35, 7.35]
                sd_list = [4.97, 4.04, 3.20]
    
            elif 45 <= patient_age <= 54:
                mean_list = [11.38, 9.76, 7.67]
                sd_list = [3.99, 4.85, 4.36]
    
            elif 55 <= patient_age <= 64:
                mean_list = [11.70, 10.57, 7.96]
                sd_list = [6.01, 6.13, 4.61]
            
            elif 65 <= patient_age:
                mean_list = [9.68, 9.58, 6.89]
                sd_list = [3.67, 4.07, 2.88]
            else:
                print("Bu yaş grubu için norm mevcut değildir.")
                norm_exists = False
        
        elif 12 <= patient_edu:
            if 15 <= patient_age <= 24:
                mean_list = [15.82, 15.11, 10.87]
                sd_list = [5.10, 4.80, 3.49]
                
            elif 25 <= patient_age <= 34:
                mean_list = [15.85, 13.08, 8.81]
                sd_list = [4.03, 3.99, 2.40]
    
            elif 35 <= patient_age <= 44:
                mean_list = [15.05, 14.29, 10.00]
                sd_list = [4.75, 5.43, 3.22]
    
            elif 45 <= patient_age <= 54:
                mean_list = [13.13, 13.88, 9.54]
                sd_list = [4.38, 4.62, 3.89]
    
            elif 55 <= patient_age <= 64:
                mean_list = [13.10, 11.81, 8.33]
                sd_list = [3.52, 4.01, 2.42]
            
            elif 65 <= patient_age:
                mean_list = [13.75, 12.80, 9.25]
                sd_list = [5.39, 4.76, 3.54]
            else:
                print("Bu yaş grubu için norm mevcut değildir.")
                norm_exists = False
        
        else:
            print("Bu eğitim grubu için norm mevcut değildir.")
            norm_exists = False
        
        std_dev_output_list = std_dev_int_calc(result_list, mean_list, sd_list)
        std_dev_verbal_list = which_sd_better_list(std_dev_output_list, more_std_dev_better)
        printable_list = printable_list_maker(result_list, std_dev_output_list, std_dev_verbal_list)

        
        test_name = 'verbal_fluency_data.csv' #test datasının toplanacağı csv dosyasını belirtiyor
        csv_writer(uygulayici, patient_ID, patient_age, patient_sex, patient_edu, test_name, printable_list)
        
        console_results = "\n===================================\nSözel akıcılık testinin sonuçları: "
        for i in range(len(mean_list)):
            console_results = console_results + (result_name[i] + str(console_result_feedback(result_list, std_dev_output_list, std_dev_verbal_list)[i]))            
        console_results = console_results + ("\n===================================\n")
        

        if norm_exists:      
            txt_writer(uygulayici, patient_ID, console_results)
            print(console_results)
            
        else:
            txt_writer(uygulayici, patient_ID, ("Sözel akıcılık: Bu grup için norm mevcut değildir.\n" + console_results))
            return
    
    
    except:
        print("Sözel akıcılık testini değerlendirirken bir hata oluştu, program kapatılacak.")
        raise
        return

def wisconsin(patient_ID, patient_age, patient_edu, patient_sex, uygulayici):
    try:
        try:
            print("\n===================================\nYetişkin Wisconsin kart eşleme: \n")
            wis_1 = int(input("Toplam tepki sayısı puanı: "))
            wis_2 = int(input("Tamamlanan kategori sayısı puanı: "))
            wis_3 = int(input("Toplam perseveretif hata sayısı puanı: "))
            wis_4 = int(input("Perseveratif hata yüzdesi puanı: "))
            result_list = [wis_1, wis_2, wis_3, wis_4]        
            
            result_name = ["\nToplam tepki sayısı puanı: " ,
                           "\nTamamlanan kategori sayısı puanı: ",
                           "\nToplam perseveretif hata sayısı puanı: ",
                           "\nPerseveratif hata yüzdesi puanı: "]               
            mean_list = []
            sd_list = []
            for i in range(len(result_list)):
                mean_list.append(result_list[i]-999)
                sd_list.append(1)      
    
            norm_exists = True
        except:
            print("Lütfen sadece rakam giriniz.")
            wisconsin(patient_ID, patient_age, patient_edu, patient_sex, uygulayici)
            
        if 5 <= patient_edu <= 11:
            if 20 <= patient_age <= 54:
                mean_list = [121.70, 3.45, 29.85, 19.22] 
                sd_list = [13.27, 1.78, 13.55, 13.17] 
                
            elif 55 <= patient_age <= 72:
                mean_list = [122.04, 3.18, 32.71, 22.36]
                sd_list = [13.43, 1.63, 13.78, 14.93]

            else:
                print("Bu yaş grubu için norm mevcut değildir.")
                norm_exists = False
                
        elif 12 <= patient_edu:
            if 20 <= patient_age <= 54:
                mean_list = [106.25, 4.98, 17.69, 15.72]
                sd_list = [21.12, 1.59, 11.11, 8.34] 
                
            elif 55 <= patient_age <= 78:
                mean_list = [104.68, 4.77, 16.77, 18.14]
                sd_list = [20.49, 1.95, 10.34, 12.30]

            else:
                print("Bu yaş grubu için norm mevcut değildir.")
                norm_exists = False
  
        else:
            print("Bu eğitim grubu için norm mevcut değildir.")
            norm_exists = False
        
        std_dev_output_list = std_dev_int_calc(result_list, mean_list, sd_list)
        std_dev_verbal_list = which_sd_better_list(std_dev_output_list, more_std_dev_better)
        printable_list = printable_list_maker(result_list, std_dev_output_list, std_dev_verbal_list)

        
        test_name = 'wisconsin_data.csv' #test datasının toplanacağı csv dosyasını belirtiyor
        csv_writer(uygulayici, patient_ID, patient_age, patient_sex, patient_edu, test_name, printable_list)
        
        console_results = "\n===================================\nYetişkin Wisconsin kart eşleme testinin sonuçları: "
        for i in range(len(result_list)):
            console_results = console_results + (result_name[i] + str(console_result_feedback(result_list, std_dev_output_list, std_dev_verbal_list)[i]))            
        console_results = console_results + ("\n===================================\n")
        

        if norm_exists:      
            txt_writer(uygulayici, patient_ID, console_results)
            print(console_results)
            
        else:
            txt_writer(uygulayici, patient_ID, ("Yetişkin Wisconsin kart eşleme: Bu grup için norm mevcut değildir.\n" + console_results))
            return
    
    
    except:
        print("Yetişkin Wisconsin kart eşleme testini değerlendirirken bir hata oluştu," +
        "program kapatılacak.")
        raise
        return



def trail_making(patient_ID, patient_age, patient_edu, patient_sex, uygulayici):
    try:
        try:
            print("\n===================================\nİz sürme testi: \n")
            tm_a = float(input("Saniye cinsinden A skoru: "))
            tm_b = float(input("Saniye cinsinden B skoru: "))
            result_list = [tm_a, tm_b]   
            
            result_name = ["\nA skoru için: ", "\nB skoru için: "]
            mean_list = []
            sd_list = []
            for i in range(len(result_list)):
                mean_list.append(result_list[i]-999)
                sd_list.append(1)      
            norm_exists = True
        except:
            print("Lütfen sadece rakam giriniz.")
            trail_making(patient_ID, patient_age, patient_edu, patient_sex, uygulayici)
        
        if patient_sex == "Kadın":
            if patient_edu <= 5:
                if 50 <= patient_age <= 54:
                    mean_list = [69.67, 108.83] #Cinsiyeti K, 5 yıldan az eğitim almış, 50-54 yaş aralığında
                    sd_list = [21.59, 15.22]#hasta için, [A skoru mean, B skoru mean] şeklinde
                
                elif 55 <= patient_age <= 59:
                    mean_list = [72.77, 127.85]
                    sd_list = [21.41, 26.90]
                
                elif 60 <= patient_age <= 64:
                    mean_list = [82.23, 141.62]
                    sd_list = [29.80, 49.28]
                
                elif 65 <= patient_age <= 69:
                    mean_list = [100.00, 168.91]
                    sd_list = [33.33, 66.00]
                
                elif 70 <= patient_age <= 74:
                    mean_list = [110.20, 235.30]
                    sd_list = [34.29, 27.84]
                    
                elif 75 <= patient_age <= 79:
                    mean_list = [158.20, 236.10]
                    sd_list = [57.48, 55.33]
                    
                elif 80 <= patient_age:
                    mean_list = [238.30, 301.10]
                    sd_list = [89.47, 78.71]
                else: 
                    print("Bu yaş aralığı için norm mevcut değildir")
                    norm_exists = False
            
            elif 6 <= patient_edu <= 11:  
                if 50 <= patient_age <= 54:
                    mean_list = [60.31, 94.92]
                    sd_list = [13.24, 16.91]
                
                elif 55 <= patient_age <= 59:
                    mean_list = [61.69, 122.15]
                    sd_list = [24.55, 27.12]
                
                elif 60 <= patient_age <= 64:
                    mean_list = [77.00, 140.10]
                    sd_list = [22.57, 30.45]
                
                elif 65 <= patient_age <= 69:
                    mean_list = [63.70, 105.70]
                    sd_list = [13.66, 28.14]
                
                elif 70 <= patient_age <= 74:
                    mean_list = [93.83, 226.50]
                    sd_list = [47.53, 105.29]
                    
                elif 75 <= patient_age <= 79:
                    mean_list = [110.50, 234.50]
                    sd_list = [44.24, 50.34]
                    
                elif 80 <= patient_age:
                    mean_list = [195.90, 309.50]
                    sd_list = [74.72, 22.07]
                else:
                    print("Bu yaş aralığı için norm mevcut değildir.")
                    norm_exists = False
                
            elif 12 <= patient_edu:
                if 50 <= patient_age <= 54:
                    mean_list = [53.53, 89.71]
                    sd_list = [10.81, 18.03]
                
                elif 55 <= patient_age <= 59:
                    mean_list = [53.14, 109.07]
                    sd_list = [13.60, 41.46]
                
                elif 60 <= patient_age <= 64:
                    mean_list = [58.00, 110.70]
                    sd_list = [20.01, 32.51]
                
                elif 65 <= patient_age <= 69:
                    mean_list = [78.60, 122.00]
                    sd_list = [31.54, 30.34]
                
                elif 70 <= patient_age <= 74:
                    mean_list = [107.60, 229.80]
                    sd_list = [43.50, 43.04]
                    
                elif 75 <= patient_age <= 79:
                    mean_list = [132.00, 186.60]
                    sd_list = [23.88, 43.74]
                    
                elif 80 <= patient_age:
                    mean_list = [183.10, 252.00]
                    sd_list = [13.43, 46.54]
                else: 
                    print("Bu yaş aralığı için norm mevcut değildir")
                    norm_exists = False
            else:
                print("Bu eğitim grubu için norm mevcut değildir.")
                norm_exists = False
                
        elif patient_sex == "Erkek":
            if patient_edu <= 5:
                if 50 <= patient_age <= 54:
                    mean_list = [88.00, 126.17]
                    sd_list = [21.90, 27.61]
                
                elif 55 <= patient_age <= 59:
                    mean_list = [69.70, 122.90]
                    sd_list = [7.67, 15.65]
                
                elif 60 <= patient_age <= 64:
                    mean_list = [78.90, 121.40]
                    sd_list = [27.02, 20.50]
                
                elif 65 <= patient_age <= 69:
                    mean_list = [97.40, 161.10]
                    sd_list = [38.74, 37.86]
                
                elif 70 <= patient_age <= 74:
                    mean_list = [89.20, 219.20]
                    sd_list = [35.39, 61.58]
                    
                elif 75 <= patient_age <= 79:
                    mean_list = [121.40, 228.50]
                    sd_list = [30.89, 43.22]
                    
                elif 80 <= patient_age:
                    mean_list = [286.40, 351.70]
                    sd_list = [28.23, 26.05]
                else: 
                    print("Bu yaş aralığı için norm mevcut değildir")
                    norm_exists = False
            
            elif 6 <= patient_edu <= 11:
                result_list[0] = int(999)
                #TM-A skoru için bu eğitim grubunda erkeklerde
                #norm olmadığı için, 999 sonucu verecek
                if 50 <= patient_age <= 54:
                    mean_list = [0, 89.47]
                    sd_list = [1, 16.69]
                
                elif 55 <= patient_age <= 59:
                    mean_list = [0, 123.91]
                    sd_list = [1, 31.00]
                
                elif 60 <= patient_age <= 64:
                    mean_list = [0, 117.08]
                    sd_list = [1, 32.79]
                
                elif 65 <= patient_age <= 69:
                    mean_list = [0, 130.15]
                    sd_list = [1, 38.78]
                
                elif 70 <= patient_age <= 74:
                    mean_list = [0, 206.80]
                    sd_list = [1, 63.31]
                    
                elif 75 <= patient_age <= 79:
                    mean_list = [0, 167.60]
                    sd_list = [1, 49.80]
                    
                elif 80 <= patient_age:
                    mean_list = [0, 2542.50]
                    sd_list = [1, 51.58]
                else: 
                    print("Bu yaş aralığı için norm mevcut değildir")
                    norm_exists = False
            
            elif 12 <= patient_edu:
                if 50 <= patient_age <= 54:
                    mean_list = [52.38, 86.25]
                    sd_list = [16.23, 23.02]
                
                elif 55 <= patient_age <= 59:
                    mean_list = [51.16, 109.07]
                    sd_list = [7.54, 41.46]
                
                elif 60 <= patient_age <= 64:
                    mean_list = [71.60, 125.40]
                    sd_list = [39.18, 56.23]
                
                elif 65 <= patient_age <= 69:
                    mean_list = [54.27, 108.55]
                    sd_list = [14.95, 31.40]
                
                elif 70 <= patient_age <= 74:
                    mean_list = [83.40, 193.90]
                    sd_list = [28.70, 71.35]
                    
                elif 75 <= patient_age <= 79:
                    mean_list = [91.10, 185.50]
                    sd_list = [43.29, 51.07]
                    
                elif 80 <= patient_age:
                    mean_list = [128.90, 226.10]
                    sd_list = [41.25, 53.64]
                else: 
                    print("Bu yaş aralığı için norm mevcut değildir.")
                    norm_exists = False              
            else:
                print("Bu eğitim grubu için norm mevcut değildir.")
                norm_exists = False
                
        else:
            print("Bu cinsiyet için norm mevcut değildir.")
            norm_exists = False
            
        std_dev_output_list = std_dev_int_calc(result_list, mean_list, sd_list)
        std_dev_verbal_list = which_sd_better_list(std_dev_output_list, more_std_dev_better)
        printable_list = printable_list_maker(result_list, std_dev_output_list, std_dev_verbal_list)


        test_name = 'trail_making_data.csv' #test datasının toplanacağı csv dosyasını belirtiyor
        csv_writer(uygulayici, patient_ID, patient_age, patient_sex, patient_edu, test_name, printable_list)

           
        console_results = "\n===================================\nİz sürme testinin sonuçları: "
        for i in range(len(mean_list)):
            console_results = console_results + (result_name[i] + str(console_result_feedback(result_list, std_dev_output_list, std_dev_verbal_list)[i]))            
        console_results = console_results + ("\n===================================\n")
        
        if norm_exists:
            txt_writer(uygulayici, patient_ID, console_results)
            print(console_results)
            
        else:
            txt_writer(uygulayici, patient_ID, ("İz sürme testi: Bu grup için norm mevcut değildir.\n"+console_results))
            return
    
    except:
        print("İz sürme testini değerlendirirken bir hata oluştu, program kapatılacak.")
        raise
        return
                     
                
def stroop(patient_ID, patient_age, patient_edu, patient_sex, uygulayici): #stroop testinin ana fonksiyonu
    try:
        try:
            print("\n===================================\nStroop Tbag: \n")
            stroop_sec1 = float(input("Bölüm 1 Tamamlama süresi puanı: "))
            stroop_sec2 = float(input("Bölüm 2 Tamamlama süresi puanı: "))
            stroop_sec3 = float(input("Bölüm 3 Tamamlama süresi puanı: "))
            stroop_sec4 = float(input("Bölüm 4 Tamamlama süresi puanı: "))
            stroop_sec5 = float(input("Bölüm 5 Tamamlama süresi puanı: "))
            result_list = [stroop_sec1, stroop_sec2, stroop_sec3, stroop_sec4, stroop_sec5]
            
            result_name = ["\nBölüm 1: ", "\nBölüm 2: ", "\nBölüm 3: ", "\nBölüm 4: ", "\nBölüm 5: "]
            
            mean_list = []
            sd_list = []
            for i in range(len(result_list)):
                mean_list.append(result_list[i]-999)
                sd_list.append(1)      
            norm_exists = True
        except:
            print("Lütfen sadece rakam giriniz.")
            stroop(patient_ID, patient_age, patient_edu, patient_sex, uygulayici)
            
        if 20 <= patient_age <= 54 and 5 <= patient_edu <= 8:
            mean_list = [12.13, 13.61, 17.46, 28.07, 40.57]
            sd_list = [6.29, 7.41, 9,60, 13.85, 24.24]     
            
        elif 55 <= patient_age <= 74 and 5 <= patient_edu <= 8:
            mean_list = [13.51, 16.47, 24.45, 38.39, 47.93]
            sd_list = [5.49, 6.76, 13.36, 18.52, 20.82]
            
        elif 20 <= patient_age <= 54 and  8 < patient_edu:
            mean_list = [8.81, 9.43, 12.32, 16.95, 26.38]
            sd_list = [1.76, 2.52, 2.71, 6.70, 12.29]
            
        elif 55 <= patient_age <= 74 and 8 < patient_edu:
            mean_list = [10.09, 11.63, 15.93, 24.87, 35.96]
            sd_list = [3.71, 5.41, 4.06, 10.94, 16.23]
            
        else:
            print("Stroop: Bu yaş veya eğitim grubu için norm mevcut değildir.") 
            norm_exists = False
        
        std_dev_output_list = std_dev_int_calc(result_list, mean_list, sd_list)
        std_dev_verbal_list = which_sd_better_list(std_dev_output_list, less_std_dev_better)
        printable_list = printable_list_maker(result_list, std_dev_output_list, std_dev_verbal_list)
        
        
        test_name = 'stroop_data.csv' #test datasının toplanacağı csv dosyasını belirtiyor
        csv_writer(uygulayici, patient_ID, patient_age, patient_sex, patient_edu, test_name, printable_list)
        
        
                       
        console_results = "\n===================================\nStroop testinin sonuçları: "
        for i in range(len(mean_list)):
            console_results = console_results + (result_name[i] + str(console_result_feedback(result_list, std_dev_output_list, std_dev_verbal_list)[i]))            
        console_results = console_results + ("\n===================================\n")
        
        if norm_exists:
            txt_writer(uygulayici, patient_ID, console_results)
            print(console_results)
            
        else:
            txt_writer(uygulayici, patient_ID, ("Stroop: Bu grup için norm mevcut değildir\n"+console_results))
            return
        
    except:
        print("Stroop testini işlerken bir hata oluştu, sistem yeniden başlatılacak.")
        raise
        return

                
def sdot(patient_ID, patient_age, patient_edu, patient_sex, uygulayici):
    try:
        try:
            print("\n===================================\nYetişkinlerde çizgi yönünü belirleme: \n")
            sdot_1 = float(input("Puan: "))
            result_list = [sdot_1]
            
            result_name = ["\nÇizgi yönü: "]
            
            mean_list = []
            sd_list = []
            for i in range(len(result_list)):
                mean_list.append(result_list[i]-999)
                sd_list.append(1)      
            norm_exists = True
        except:
            print("Lütfen sadece rakam giriniz.")
            sdot(patient_ID, patient_age, patient_edu, patient_sex, uygulayici)
            
        if 20 <= patient_age <= 54 and 5 <= patient_edu <= 8:
            mean_list = [20.03]
            sd_list = [4.58]     
            
        elif 55 <= patient_age <= 74 and 5 <= patient_edu <= 8:
            mean_list = [19.81]
            sd_list = [4.00]
            
        elif 20 <= patient_age <= 54 and  9 <= patient_edu <= 11:
            mean_list = [22.46]
            sd_list = [4.52]
            
        elif 55 <= patient_age <= 76 and 9 <= patient_edu <= 11:
            mean_list = [21.18]
            sd_list = [4.82]
            
        elif 20 <= patient_age <= 54 and 12 <= patient_edu:
            mean_list = [25.37]
            sd_list = [3.51]
            
        elif 55 <= patient_age <= 73 and 12 <= patient_edu:
            mean_list = [23.04]
            sd_list = [3.43]
            
        else:
            print("Çizgi yönü: Bu yaş veya eğitim grubu için norm mevcut değildir.") 
            norm_exists = False
        
        std_dev_output_list = std_dev_int_calc(result_list, mean_list, sd_list)
        std_dev_verbal_list = which_sd_better_list(std_dev_output_list, more_std_dev_better)
        printable_list = printable_list_maker(result_list, std_dev_output_list, std_dev_verbal_list)
        
        
        test_name = 'sdot_data.csv' #test datasının toplanacağı csv dosyasını belirtiyor
        csv_writer(uygulayici, patient_ID, patient_age, patient_sex, patient_edu, test_name, printable_list)
        
        
                       
        console_results = "\n===================================\nÇizgi yönünü belirleme testinin sonuçları: "
        for i in range(len(mean_list)):
            console_results = console_results + (result_name[i] + str(console_result_feedback(result_list, std_dev_output_list, std_dev_verbal_list)[i]))            
        console_results = console_results + ("\n===================================\n")
        
        if norm_exists:
            txt_writer(uygulayici, patient_ID, console_results)
            print(console_results)
            
        else:
            txt_writer(uygulayici, patient_ID, ("Çizgi yönü: Bu grup için norm mevcut değildir\n"+console_results))
            return
        
    except:
        print("Çizgi yönü testini işlerken bir hata oluştu, sistem yeniden başlatılacak.")
        raise
        return


#these variables were got before
def sbst(patient_ID, patient_age, patient_edu, patient_sex, uygulayici): 
    try:
        while True:
            try:
                print("\n===================================\nSBST: ")
                result_name = ["\nKendiliğinden hatırlama boyutu: ", "\nTanıma boyutu: ", 
                "\nToplam hatırlama boyutu: ",  "\nHatırlama yanlışı boyutu: ", 
                "\nYanlış tanıma boyutu: ", "\nA listesi anlık bellek boyutu: ", 
                "\nA listesi toplam öğrenme boyutu: "]  
                #prints user interface
                
                sbst_8 = float(input(result_name[0]))
                sbst_10 = float(input(result_name[1]))
                sbst_11 = float(input(result_name[2]))
                sbst_9 = float(input(result_name[3]))
                sbst_12 = float(input(result_name[4]))
                sbst_1 = float(input(result_name[5]))
                sbst_2 = float(input(result_name[6]))
                #gets raw input from the user, these are test results
                
                result_list = [sbst_8, sbst_10, sbst_11, sbst_9, sbst_12, sbst_1, sbst_2]
                mean_list = []
                sd_list = []
                #creates a list for the test results, and empty ones 
                #for the means and standard deviations
                for i in range(len(result_list)):
                    mean_list.append(result_list[i]-999)
                    sd_list.append(1)            
                    #makes it so that it prints out 999 if there's 
                    #no norm calculated for that group
                norm_exists = True
                #It assumes that there's a norm for every group
                #if none exists, it changes to False
                
            except:
                print("Lütfen sadece rakam giriniz.")
                sbst(patient_ID, patient_age, patient_edu, patient_sex, uygulayici)
                continue
                #"Only enter numbers", and then resets the function
            
            else:
                break
            
            #tries to get user input, makes sure it's correct input
            
            
            """
            Following are lists of means and standard deviations,
            of the specified age, education and sex, where it applies.
            It's in a way that it corresponds to order of the
            result_list.
            """
        if patient_edu <= 7:
            if 15 <= patient_age <= 39:
                mean_list = [13.64, 1.21, 14.86, 0.24, 0.04, 5.50, 116.27]
                sd_list = [1.20, 1.16, 0.35, 0.51, 0.19, 1.64, 10.74]
                
            elif 40 <= patient_age <= 49:
                mean_list = [13.27, 1.69, 14.97, 0.15, 0.08, 5.32, 109.11]
                sd_list = [1.24, 1.21, 0.18, 0.40, 0.27, 1.35, 11.94]
                
            elif 50 <= patient_age <= 59:
                mean_list = [13.24, 1.74, 14.98, 0.15, sbst_12, 5.08, 113.50] #Aslında sbst_12 mean = 0.00, SD = 0.00
                sd_list = [1.38, 1.37, 0.12, 0.40, 1, 1.03, 12.00]
            
            elif 60 <= patient_age <= 69:
                mean_list = [12.90, 2.27, 14.94, 0.20, 0.02, 5.10, 107.80]
                sd_list = [1.36, 2.04, 0.24, 0.46, 0.14, 1.37, 11.16]
            
            elif 70 <= patient_age <= 79:
                mean_list = [12.93, 2.02, 14.96, 0.24, 0.02, 5.00, 103.69]
                sd_list = [1.44, 1.39, 0.21, 0.43, 0.15, 1.09, 14.21]
                
            elif 80 <= patient_age:
                mean_list = [10.35, 4.35, 14.70, 0.26, 0.30, 3.96, 88.96]
                sd_list = [1.72, 1.58, 0.64, 0.45, 0.56, 1.66, 14.02]
                
            else: 
                print("Bu yaş aralığı için norm mevcut değildir.")
                norm_exists = False     
                #"No norm exists for the group", sets it to False
                
        elif 8 <= patient_edu <= 19:
            if 15 <= patient_age <= 39:
                mean_list = [14.00, 0.97, 14.97, 0.13, sbst_12, 7.87, 131.21] #Aslında sbst_12 mean = 0.00, SD = 0.00
                sd_list = [1.05, 1.04, 0.16, 0.45, 1, 2.05, 10.61]
                
            elif 40 <= patient_age <= 49:
                mean_list = [13.62, 1.29, 14.91, 0.15, 0.03, 6.98, 126.12]
                sd_list = [1.39, 1.27, 0.29, 0.40, 0.17, 1.96, 11.25]
                
            elif 50 <= patient_age <= 59:
                mean_list = [13.45, 1.54, 14.97, 0.13, 0.03, 6.61, 124.22]
                sd_list = [1.29, 1.28, 0.17, 0.34, 0.17, 1.50, 10.48]
            
            elif 60 <= patient_age <= 69:
                mean_list = [13.64, 1.22, 14.88, 0.12, sbst_12, 5.94, 116.88]#Aslında sbst_12 mean = 0.00, SD = 0.00
                sd_list = [1.10, 0.91, 0.39, 0.39, 1, 1.33, 11.15]
            
            elif 70 <= patient_age <= 79:
                mean_list = [12.29, 2.63, 14.94, 0.13, 0.04, 5.27, 109.75]
                sd_list = [11.88, 1.75, 0.24, 0.34, 0.20, 1.45, 13.98]
                
            elif 80 <= patient_age:
                mean_list = [11.88, 3.02, 14.89, 0.18, 0.09, 5.19, 109.68]
                sd_list = [1.72, 1.63, 0.36, 0.47, 0.34, 1.64, 16.80]
            else: 
                print("Bu yaş aralığı için norm mevcut değildir.")
                norm_exists = False  
        else:
            print("Bu eğitim grubu için norm mevcut değildir.")
            norm_exists = False  
                
                
        
        std_dev_output_list = std_dev_int_calc(result_list, mean_list, sd_list)
        #it calculated the patient's SD interval as a float using the results, means and the SD
        std_dev_verbal_list = which_sd_better_list(std_dev_output_list, more_std_dev_better)
        #Makes a verbal list to input to the users
        printable_list = printable_list_maker(result_list, std_dev_output_list, std_dev_verbal_list)
        #creates a list to be put into a CSV file

        test_name = 'SBST_data.csv' #test datasının toplanacağı csv dosyasını belirtiyor
        csv_writer(uygulayici, patient_ID, patient_age, patient_sex, patient_edu, test_name, printable_list)
        #writes the printable_list in a CSV file
        
              
        console_results = "\n===================================\nSBST testinin sonuçları:"
        for i in range(len(mean_list)):
            console_results = console_results + (result_name[i] + str(console_result_feedback(result_list, std_dev_output_list, std_dev_verbal_list)[i]))            
        console_results = console_results + ("\n===================================\n")
        #prints the list using the range of the list and makes it more appealing for the user (probably should've used a decorator here)
        
        if norm_exists:
            txt_writer(uygulayici, patient_ID, console_results)
            print(console_results)
            #creates a patient report for the physician and prints it out for the user
        else:
            txt_writer(uygulayici, patient_ID, ("SBST: Bu grup için norm mevcut değildir.\n"+console_results))
            return
            #if there's no norm, it puts "there's no norm for this group" in the patient report
    
    except:
        print("SBST testini değerlendirirken bir hata oluştu, program kapatılacak.")
        raise
        return
        #saves the program from fiery death
        
        

def rkft(patient_ID, patient_age, patient_edu, patient_sex, uygulayici):
    try:
        try: 
            print("\n===================================\nRey karmaşık figür testi: ")
            result_name = ["\nKopyalama: ", "\nAnlık hatırlama: ", 
            "\nGecikmeli hatırlama: ",  "\nTanıma doğru pozitif puanı: ", 
            "\nTanıma yanlış pozitif puanı: "]  
            
            rey_1 = float(input(result_name[0]))
            rey_2 = float(input(result_name[1]))
            rey_3 = float(input(result_name[2]))
            rey_4 = float(input(result_name[3]))
            rey_5 = float(input(result_name[4]))
            
            
            
            result_list = [rey_1, rey_2, rey_3, rey_4, rey_5]
            mean_list = []
            sd_list = []
            for i in range(len(result_list)):
                mean_list.append(result_list[i]-999)
                sd_list.append(1)            
            norm_exists = True
        except:
            print("Lütfen sadece rakam giriniz.")
            rkft(patient_ID, patient_age, patient_edu, patient_sex, uygulayici)
        
        if patient_edu < 8:
            if 17 <= patient_age <= 49:
                mean_list = [29.90, 14.45, 14.35, 10.37, 2.63]
                sd_list = [5.277, 5.604, 5.992, 1.71, 1.56]
                
            elif 50 <= patient_age <= 60:
                mean_list = [27.3, 13.3, 13.5, 10, 2.50]
                sd_list = [6.391, 4.461, 4.577, 1.05, 1.65]
                
            elif 61 <= patient_age <= 71:
                mean_list = [27.05, 10.3, 8.85, 9.7, 2.4]
                sd_list = [4.764, 4.656, 4.308, 1.7, 1.78]
            
            elif 72 <= patient_age <= 82:
                mean_list = [24.3, 8.3, 7.55, 10.3, 3.2]
                sd_list = [5.673, 5.089, 4.919, 1.7, 1.99]
            else: 
                print("Bu yaş aralığı için norm mevcut değildir.")
                norm_exists = False     
                
        elif 8 <= patient_edu:
            if 17 <= patient_age <= 49:
                mean_list = [33.096, 19.75, 18.84, 9.73, 1.27]
                sd_list = [2.548, 4.993, 5.062, 1.74, 1.17]
                
            elif 50 <= patient_age <= 60:
                mean_list = [32.75, 16.7, 16.25, 10.2, 1.55]
                sd_list = [3.263, 4.998, 5.175, 1.4, 1.39]
                
            elif 61 <= patient_age <= 71:
                mean_list = [31.125, 14.525, 14.35, 9.45, 1.8]
                sd_list = [3.947, 6.315, 6.796, 1.9, 1.54]
            
            elif 72 <= patient_age <= 82:
                mean_list = [28.6, 10.975, 11.025, 9.1, 2.2]
                sd_list = [3.192, 4.805, 5.466, 1.83, 1.67]
            else: 
                print("Bu yaş aralığı için norm mevcut değildir.")
                norm_exists = False  
        else:
            print("Bu eğitim grubu için norm mevcut değildir.")
            norm_exists = False  
                
                
        
        std_dev_output_list = std_dev_int_calc(result_list, mean_list, sd_list)
        std_dev_verbal_list = which_sd_better_list(std_dev_output_list, more_std_dev_better)
        printable_list = printable_list_maker(result_list, std_dev_output_list, std_dev_verbal_list)


        test_name = 'rey_data.csv' #test datasının toplanacağı csv dosyasını belirtiyor
        csv_writer(uygulayici, patient_ID, patient_age, patient_sex, patient_edu, test_name, printable_list)
        
        
              
        console_results = "\n===================================\nRey karmaşık figür testinin sonuçları:"
        for i in range(len(mean_list)):
            console_results = console_results + (result_name[i] + str(console_result_feedback(result_list, std_dev_output_list, std_dev_verbal_list)[i]))            
        console_results = console_results + ("\n===================================\n")
        
        
        if norm_exists:
            txt_writer(uygulayici, patient_ID, console_results)
            print(console_results)
            
        else:
            txt_writer(uygulayici, patient_ID, ("Rey: Bu grup için norm mevcut değildir.\n"+console_results))
            return
    
    except:
        print("Rey testini değerlendirirken bir hata oluştu, program kapatılacak.")
        raise
        return


        
while True:
    startup()
    
    print("\n===================================\n" +
    "Bilgiler başarıyla girildi, yeniden başlatılıyor.")
    
