print("Labdien! Šī programma jums palīdzēs apgūt pyton programmēšanas pamatus.Jums būs iespēja apgūt 5 dažādas tēmas un pēc tām izpildīt 10 jautājumu testu, lai pārbaudītu jūsu zināšanas!")
print()
atbilde=input("Vai vēlies sākt apgūt 1.tēmu?(Atbildi ar Jā un Nē):")
print()
if atbilde=="Jā":
    print("1.Tēma-Print un Input.Programmā Python mēs varam vienkārši izmantot funkciju print(), lai izdrukātu izvadi.Piem:Print(^Labrīt!^),Print(^Šodien ir lietains lakis.^)Lietotās redz-Labrīt!Šodien ir lietains laiks.Programmēšanas laikā mēs, iespējams, vēlamies saņemt ievadi no lietotāja. Python mēs varam izmantot funkciju input (). Piem: Input(Kāda ir tava mīļākā krāsa?)Programa lietotājs uz ekrāna redzās šo jautājumu un varēs ierakstīt atbildi.")
else:
    print("Jūsu apmācība ir beigusies.")/n
print()    
atbilde=input("Vai vēlies turpināt apmācību?(Atbildi ar Jā un Nē):")
print()
if atbilde=="Jā":
    print("2.Tēma-Mainīgie Mainīgajiem ir svarīga loma Python programmēšanā, jo tie ļauj mums uzglabāt un manipulēt ar datiem. Būtībā mainīgais ir nosaukts konteiners, kurā ir vērtība, kas var būt dažāda veida, piemēram, skaitļi, virknes vai pat sarežģītākas datu struktūras, piemēram, saraksti vai vārdnīcas. Mainīgo lielumu izmantošanas mērķis ir nodrošināt veidu, kā saglabāt un atsaukties uz datiem visā programmā, atvieglojot koda rakstīšanu un izpratni.Lai programmā varētu izmantot mainīgo, vispirms tas ir jādefinē - jānosaka tā nosaukums un tips. Tas ir jādara vēl pirms programmas galvenās daļas (starp begin ... end.)")
else:
    print("Jūsu apmācība ir beigusies.")/n
print()
atbilde=input("Vai vēlies turpināt apmācību?(Atbildi ar Jā un Nē):")
print()
if atbilde=="Jā":
    print("3.Tēma-Cikli Programmā Python ir pieejami divi pamata ciklu veidi: cikls for un while cikls, un katrs no tiem kalpo atšķirīgiem mērķiem un atbilst dažādām programmēšanas prasībām. Cikls for tiek izmantota, lai atkārtotu secību. Šīs Python secības ir datu struktūras: saraksts, virkne, vārdnīca, kopa vai virkne. Cikla For izpilda koda bloku katram secības vienumam. Cikls while ir nosacījuma cikls. Tas nozīmē, ka tas tiek izpildīts tik ilgi, kamēr pastāv konkrēts nosacījums, kas ir True. Tas ir īpaši noderīgi, ja iterāciju skaits nav iepriekš zināms.(iterācija-Iterācija ir procesa atkārtošana, lai ģenerētu rezultātu secību (iespējams, neierobežotu) ar mērķi tuvoties vēlamajam mērķim vai rezultātam. Cik reizes tu izmanto noteikto ciklu tik iterācijas ir veiktas)")
else:
    print("Jūsu apmācība ir beigusies.")/n
print()
atbilde=input("Vai vēlies turpināt apmācību?(Atbildi ar Jā un Nē):")
print()
if atbilde=="Jā":
    print("4.Tēma-Sazarojumi If nosacijums then komanda If nosacijums then komanda1 else komanda2(Burtiski tulkojot uz latviešu valodu sanāk: ja ... tad ... un ja ... tad ... citādi ...)Par nosacījumu var izmantot jebkuru izteiksmi, kura pieņem vērtības True vai False. Ja šīs izteiksmes vērtība ir True, tad tiek izpildītas komandas pēc then. Ja vērtība ir False un ir izmantots else, tad tiek izpildītas komandas aiz else.")
else:
    print("Jūsu apmācība ir beigusies.")/n
print()
atbilde=input("Vai vēlies turpināt apmācību?(Atbildi ar Jā un Nē):")
print()
if atbilde=="Jā":
    print("5.Tēma–Skaitļi Funkcija Int aprēķina skaitļa veselo daļu (atmet ciparus aiz komata) un dod rezultātu ar tipu real. Funkcija Round noapaļo skaitli līdz tuvākajam veselam skaitlim (tādos gadījumos kā 4.5 vai -5.5 noapaļo tā, lai absolūtā vērtība būtu lielāka - uz 5 un -6). Rezultātam ir tips real. Ja funkciju Random izsauc bez jebkāda parametra, tad tā dod real tipa vērtību no 0 līdz 1 (skaitli 1 neieskaitot). Piem:Random*4 dod skaitļus no 0 līdz 4 (skaitli 4 neieskaitot) Random-1 dod skaitļus no -1 līdz 0 (skaitli 0 neieskaitot) Random(5) dod skaitļus no 0 līdz 4.")
else:
    print("Jūsu apmācība ir beigusies.")/n
print()

input("Vai tu vēlies pārbaudīt savas zināšanas ?(Atbildi tikai ar Jā un Nē)")
print()
if atbilde=="Jā":
    print("Jautājumi:")

vards=input("Ievadi savu vārdu:")
correct = 0
incorrect = 0
ans=input("1. Vai funkcija “print” ļauj lietotājam, pēc teksta ka parādās ekrānā, ierakstīt atbildi uz doto jautājumu/teikumu?:")
atb2=("Nē")
if(ans==atb2):
        correct = correct + 1
else:
        incorrect + 1
ans2=input("2. Vai taisnība ka sazarotajā algoritmā var ievadīt nosacijumu un 2 komandas pēc tā?:")
atb1=("Jā")
if(ans==atb1):
        correct = correct + 1
else:
        incorrect + 1
ans3=input("3.Vai taisnība ka mainīgie jāievieš pašās programmas beigās?:")
if(ans==atb2):
        correct = correct + 1
else:
        incorrect + 1
ans4=input("4.Vai taisnība ka ciklā while tas tiek izpildīts tik ilgi, kamēr lietotājs neierasta atbildi kas atbilst dotam nosacijumam?:")
if(ans==atb1):
        correct = correct + 1
else:
        incorrect + 1
ans5=input("5.Vai taisnība ka funkcija int noapaļo doto akaitli?:")
if(ans==atb2):
        correct = correct + 1
else:
        incorrect + 1
ans6=input("6.Vai taisnība ka dažos gadījumos vienalga vai izvadīt tekstu ar funkciju input vai print?:")
if(ans==atb1):
        correct = correct + 1
else:
        incorrect + 1
ans7=input("7.Vai taisnība ka izmantojot skaitļu funkciju Random*6 prorammma nekad neizvadīs saitli 6?:")
if(ans==atb1):
        correct = correct + 1
else:
        incorrect + 1
ans8=input("8.Vai proramā var izmmantot 2 mainīos ar vienādu nosaukummu?:")
if(ans==atb2):
        correct = correct + 1
else:
        incorrect + 1
ans9=input("9.Vai taisnība ka sazarotajā algaritmā, ja vērtība ir True, tad tiek izpildītas komandas pēc then?:")
if(ans==atb1):
        correct = correct + 1
else:
        incorrect + 1
ans10=input("10.Vai Cikls for tiek izmantota, lai atkārtotu secību?:")
if(ans==atb1):
        correct = correct + 1
else:
        incorrect + 1

print()
print("Apsveicu! Jūs esat pabeidzis apmācību. Jūs testā ieguvāt " + str(correct)  + " punktus no 10.")

print()






