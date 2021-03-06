# Usability Evaluation and Prototyping (again)
> Usability Evaluation in this assignment is to evaluate your high-fidelity interactive-prototype with two participants:
> the participant from the previous Contextual Inquiry (CI) 
> and an additional novice-participant with different demographics if possible.
> Respectively, revise your prototype as an attempt to fix any problems found in this Usability Evaluation.

## Operating the Prototype

[![High Fidelity Prototype](http://img.youtube.com/vi/8f0YvGWfhFQ/0.jpg)](http://www.youtube.com/watch?v=8f0YvGWfhFQ "High Fidelity Prototype")

Link: https://invis.io/GSRTBFZAHD3

---

## Part A: Usability Evaluation

### 1. Brief Description of Participants

#### a. Description of Participant 1
 - A Male Student
 - 20 Years old
 - Study at ITS, Departement of Electrical Engineering
 - Medium Level of IT Knowledge
 - Note: This is a new person to try the prototype

#### b. Description of Participant 2
 - A Female Student
 - 21 Years old
 - Study at ITS, Departement of Perencanaan Wilayah dan Perkotaan
 - Medium-low Level of IT Knowledge
 - Frequent Online Shopping users
 - Note: Same person like in assignment 1


### 2. Evaluation Script
1. User open the webshop
2. User buying something

### 3. Transcript

#### a. Transcript with Participant 1
```
1. Me: Aku minta tolong dong, tes prototype online shop Sahabat Kereta versi aku. Dibukanya pakai PC ya....
2. Him: Boleh, bisa kucoba
3. Me: Okelah
4. Him: Ada beberapa sih yang harus dibenahi. Jadi gini, pertama, bagian nama buat di seragam, nama dada, dan keychain namanya lebih baik pakai isian singkat. Sama yang terakhir websitenya lumayan terzoom
5. Me: Namanya juga prototype, tapi kalau masalah isian bukannya mending seperti itu ya buat mencegah bisa diisi pakai nama palsu? Seperti daftar email ITS itu yang namanya udah ditentukan
6. Him: Sebenarnya bisa dicocokan kalau menggunakan database, jadi meskipun pakai isian singkat tapi kalau nama tidak sesuai database yaudah failed
7. Me: Bisa-bisa, ada lagi?
8. Him: Untuk interface tidak ada masalah sih
9. Me: Okedeh, terima kasih yaaaaa....
10. Him: Sama-sama
```

#### b. Transcript with Participant 2
```
1. Me: Aku boleh minta tolong lagi gak? 
2. Her: Apa?
3. Me: Cobain prototype webshop Sahabat Kereta yang terbaru yang sudah aku rubah
4. Her: Oke
5. Her: Kalau menurutku, tampilannya kebesaran banget jadi ya harus ngescroll, sama yang kedua kasih background stasiun atau kereta gitu biar gak sepi dan putih aja, hehehe
6. Me: Okedeh, itu aja? Yaudah, makasih ya....
7. Her: Sama-sama
 ```

### 4. Feedback and Incidence Analysis
> Record your observations per prototype screen followed by reference, feedback, incidence, reason, and resolution.

#### OBSERVATION 1
![Prototype Screen 1](https://raw.githubusercontent.com/hci-a-if-its-2019/assignment-3-akmal1997/master/gambar%20pendukung/seragam1.jpg)

 - **Reference**: Line number 4 (Participant 1)
 - **Feedback**: For the name selection, it's better using own type and for the protect to not using fake name, the website must linked to database
 - **Incidence**: No
 - **Reason**: The InVision app cannot make the `<input>` element. So, i choose to make a radio button for the prototype 
 - **Resolution**: Change the name choice to `<input>` element if we make the real prototype using web programming
 
#### OBSERVATION 2
![Prototype Screen 2](https://raw.githubusercontent.com/hci-a-if-its-2019/assignment-3-akmal1997/master/gambar%20pendukung/highfidel2.jpg)

 - **Reference**: Line number 4 (Participant 1) and Line number 5 (Participant 2)
 - **Feedback**: Too large for the product and menus
 - **Incidence**:
 ![Picture]( https://raw.githubusercontent.com/hci-a-if-its-2019/assignment-3-akmal1997/master/gambar%20pendukung/messageImage_1556786052021.jpg)
The picture is from the participant computer
 - **Reason**: Because diffrent screen resolutions between my computer and participant computer. My computer using 1920x1080 pixels and the participant computer using 1366x768 pixels
 - **Resolution**: Maybe no modifications on this section, because it's only technical problems in screen resolutions
 
 #### OBSERVATION 3
![Prototype Screen 2](https://raw.githubusercontent.com/hci-a-if-its-2019/assignment-3-akmal1997/master/gambar%20pendukung/highfidel2.jpg)

 - **Reference**: Line number 5 (Participant 2)
 - **Feedback**: Add some background to make the webshop look not too simple
 - **Incidence**: Nope
 - **Reason**: I just modified from the original version and using same white background
 - **Resolution**: No Modifications because if i add some background, it will maybe make the user harder to read some text
 ---

## Part B: Prototyping (again)
> Next, you will need to modify your prototype 
> based on the resolutions you have suggested in `Feedback and Incidence Analysis`'s observations.

### Sketch
> Draw a sketch of your prototype that is refined based according to the aforementioned observations on a paper.
> Afterwards, scan the sketch or make the photograph of it and attach it on this report's section.
> Please make sure the any texts on the sketch are readable.

There is no changes from the second Assignment. But, i draw again because i combine many sketches that i draw from here: https://github.com/hci-a-if-its-2019/assignment-2-akmal1997

![Sketch of Refined Prototype](https://cdn2.hubspot.net/hub/725165/file-3421843765-png/blog-files/uxpin--300x211.png)

### Design Rationale
> Please write a paragraph expressing what you have learned from the usability evaluation, 
> and how it is reflected in your design.

From the Usability Evaluation, we can conclude that for the web page, it can be easier as long as the user feedback is positive and easy to use.

Yes, for the shop is much easier to use and more intuitive especially if we access in Touchscreen input like some laptop, ultrabooks, and large tablets. You can swipe for choosing the products. But, there are some feedback but it's only minor feedback (Like a look for the webshop, and the `<input>` form in Name section (But it's impossible to make with InVision app) but with name checker to linked to database). For the colour preferences there isn't feedback about that. But, as long the colour is acceptable and don't make users confuse and not want to buy in webshop again (And also negative feedback for colouring too), it's okay we can implement it

### High-Fidelity Interactive-Prototype
> Create a high-fidelity interactive-prototype based on the `Sketch` you have drawn.
> You can use any prototyping tools: InVision, Adobe XD, or even Microsoft PowerPoint.

https://invis.io/GSRTBFZAHD3

Because the project is overquota. You can access it from here: http://imk-akmal.mujahid-pbkk.site/prototypeskwebshop/index.html

