a = {
    "dr. baseera a": "G-01",
    "dr. vinod bhatt": "G-02",
    "dr. g. vishnuvarthanan": "G-03",
    "dr. manisha jain": "G-04",
    "dr. ribu methew": "G-05",
    "dr. manoja acharya": "G-06",
    "dr. paras jain": "G-07",
    "dr. lakshmi d.": "G-08",
    "dr. pushpinder singh patheja": "G-09",
    "dr. dev brat gupta": "G-10",
    "dr. anant kant shukla": "G-11",
    "dr. javed khan sheikh": "G-12",
    "dr. sandeep monga": "G-13",
    "dr. nikhil pateria": "G-13",
    "dr. g.r. hemalakshmi": "G-14",
    "dr. venkat padhy": "G-15",
    "nagarajan i": "G-16",
    "vijay kumar trivedi": "G-17",
    "dr. abha sharma": "G-18",
    "dr. dileep kumar": "G-19",
    "d. harish babu": "G-20",
    "j.p. shritharanyaa": "G-21",
    "dr. buvaneswari": "G-22",
    "dr. praveen lalwani": "A-101",
    "dr. sheetal sharma": "A-102",
    "i. jasmine selvakumari jeya": "A-103",
    "ar. poonam upadhyay": "A-104",
    "board room": "A-105",
    "dr. kumar abhishek": "A-106",
    "dr. suparna patowary": "A-107",
    "dr. arun kumar k.": "A-108",
    "dr. hemant kumar nashine": "A-109",
    "dr. reena jain": "A-110",
    "dr. ranju yadav": "A-111",
    "dr. chandrabhan seniya": "A-112",
    "dr. faisal rasheed lone": "A-113",
    "dr. sajjad ahmed": "A-114",
    "sripriyan": "A-115",
    "mr. abhishek kumar shukla": "A-116",
    "azra nazir": "A-117",
    "ms manorama chouhan": "A-118",
    "arindam sadhukhan": "A-119",
    "ajay sharma": "A-120",
    "bhupendra panchal": "A-121",
    "pranshu pranjal": "A-122",
    "mamta agarwal": "A-201",
    "dr. pon harshavardhanan": "A-202",
    "navneet kumar verma": "A-203",
    "shweta mukherjee": "A-204",
    "dr. subash chandra bose": "A-205",
    "dr. sasmita padhy": "A-206",
    "dr. sandip mal": "A-207",
    "dr. preetam suman": "A-208",
    "karishma tiwari": "A-209",
    "balaguru s": "A-210",
    "dr vinesh kumar": "A-211",
    "dr. a usha ruby": "A-212",
    "dr. ranjeeta kumar": "A-213",
    "dr. m. manimaran": "A-214",
    "dr. s. devaraju": "A-215",
    "harish chandra": "A-216",
    "dr. dheresh soni": "A-217",
    "dr. gopal s tandel": "A-218",
    "jaynthi j.": "A-219",
    "ujjwal kumar mishra": "A-220",
    "mr. jay prakash maurya": "A-221",
    "chandrama swain": "A-222",
    "dr. abdul rehman": "A-223",
    "dr. s. aanjankumar": "A-224",
    "karthik rao m c": "A-225",
    "dr. vijay kumar patidar": "A-226",
    "dr. rajdeep ghosh": "A-227",
    "dr. umakanta meher": "A-228",
    "abhishek shrivastava": "A-229",
    "mr. ashish kumar kesarwany": "A-230",
    "vacant": "A-231",
    "vijay kumar patel": "A-232",
    "suchismita patra": "A-233",
    "rahul kumar chaturvedi": "A-234",
    "Dr. Shahana Gajala Qureshi": "A-235",
    "Swati Chauhan": "A-236",
    "Anil Kumar Shukla": "A-237",
    "Dr. Juhi Yasmeen": "A-238",
    "Dr. Vivek Parashar": "A-239",
    "Dr. Kiran Pandey": "A-240",
    "Dr. A Balaji": "A-241",
    "Dr. Siddharth S Chouhan": "A-242",
    "Dr. Sivasankaran": "A-243",
    "Dr. Ankur Beohar": "A-244",
    "Dr. Siddartha Maiti": "A-245",
    "Dr. Soumitra Keshari Nayak": "A-246",
    "Dr. Swagat Samantray": "A-247",
    "Dr. Rajeev": "A-248",
    "Dr Sarvanan D": "A-249",
    "Dr Prashant GK": "A-250",
}
while True:
    b=input("enter if you are a user(1)/owner(2)").lower()
    if b == "1" or b== "user":
        c = input("Enter the name (or part of the name) of the faculty: ").lower()

        found = False

        for key in a:
            if c in key.lower():
                print(f"{key} : {a[key]}")
                found = True

        if not found:
            print("Data not available")
    if b == "2" or b == "owner":
        e=input("enter your username")
        f=input("enter your password")
        if e == "Gaurav" and f == "VITBPL":
            g=input("enter if you want to add/delete faculty(add(1)/delete(2))")
            while True:
                if g == "add" or g == "1":
                    h=input("enter the faculty")
                    i=input("enter the cabin")
                    j=input("check if the details are correctY/N faculty:"+h+" cabin: "+i).upper()
                    if j == "Y":
                        a.update({h:i})
                        break
                    elif j =="N":
                        l = input("Do you want to update details(1)/exit(2)")
                        if l == "2":
                            break
                
                elif g == "delete" or g == "2":
                    k=input("enter the name of faculty you want to remove")
                    del a[k]
                    break
            else:
                print("enter valid argument")
        else:
            print("wrong username/password")
            break
    d = input("do you want to exit(1)/not exit(2)")
    if d == "1" or d == "exit":
        break
