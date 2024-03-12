Pekan 5:

Screenshot JMeter GUI /all-student-name dan /highest-gpa sebelum refactor:

/all-student-name
<img src="SS_README/Screenshot (251).png">
<img src="SS_README/Screenshot (252).png">
<img src="SS_README/Screenshot (253).png">
<img src="SS_README/Screenshot (254).png">

/highest-gpa
<img src="SS_README/Screenshot (247).png">
<img src="SS_README/Screenshot (248).png">
<img src="SS_README/Screenshot (249).png">
<img src="SS_README/Screenshot (250).png">

Screenshot JMeter command line /all-student-name dan /highest-gpa sebelum refactor:

/all-student-name
<img src="SS_README/Screenshot (235).png">

/highest-gpa
<img src="SS_README/Screenshot (236).png">



Screenshot optimize /all-student:

Sebelum refactor
<img src="SS_README/Screenshot (222).png">

Setelah refactor
<img src="SS_README/Screenshot (223).png">


Screenshot optimize /all-student-name:

Sebelum refactor
<img src="SS_README/Screenshot (225).png">

Setelah refactor
<img src="SS_README/Screenshot (230).png">



Screenshot optimize /highest-gpa:

Sebelum refactor
<img src="SS_README/Screenshot (229).png">

Setelah refactor
<img src="SS_README/Screenshot (228).png">




Screenshot JMeter GUI /all-student-name dan /highest-gpa setelah refactor:

/all-student-name
<img src="SS_README/Screenshot (257).png">
<img src="SS_README/Screenshot (258).png">
<img src="SS_README/Screenshot (259).png">
<img src="SS_README/Screenshot (260).png">

/highest-gpa
<img src="SS_README/Screenshot (261).png">
<img src="SS_README/Screenshot (262).png">
<img src="SS_README/Screenshot (263).png">
<img src="SS_README/Screenshot (264).png">







Refleksi:
1. What is the difference between the approach of performance testing with JMeter and
profiling with IntelliJ Profiler in the context of optimizing application performance? 

Salah satu perbedaan profiling antara Jmeter dan IntelliJ adalah tipe profiling yang dilakukan. Jmeter menggunakan thread group untuk menilai performa program dengan beberapa thread, sedangkan IntelliJ menggunakan 
recording yang akan ditampilkan dalam flame graph, method list, timeline, dan lainnya. Hal ini menunjukkan bahwa Jmeter menggunakan Thread Profiling, sedangkan IntelliJ menggunakan CPU dan Memory Profiling.


2. How does the profiling process help you in identifying and understanding the weak points
in your application?

Profiling telah membantu saya mencari tahu kelemahan dari program saya dari segi waktu dan pemakaian memori. Sebagai contoh dengan flame graph IntelliJ, saya dapat mencari tahu mana method yang paling menguras
CPU dan memori sehingga saya dapat memperbaikinya dengan refactoring. Setelah refactoring saya juga bisa membandingkan performa kode saya sekarang dengan hasil sebelumnya untuk mendapat hasil terbaik dan tercepat.

3. Do you think IntelliJ Profiler is effective in assisting you to analyze and identify
bottlenecks in your application code?

Ya, karena performa kode bukanlah sesuatu yang bisa diperhitungkan dalam keadaan statis atau tidak berjalan. Alat-alat profiling seperti IntelliJ Profiler membantu saya mengukur performa kode saya serta memberi tahu
mana titik lemah yang masih bisa diperbaiki.

4. What are the main challenges you face when conducting performance testing and
profiling, and how do you overcome these challenges?

Kesulitan terbesar saya selama melakukan modul ini adalah mencari tahu cara refactor yang dapat mengurangi 20% waktu kode, tidak kurang dari angka tersebut. Terkadang saya juga harus menghadapi error karena refactor
yang gagal dan malah membuat program tidak jalan sama sekali.

5. What are the main benefits you gain from using IntelliJ Profiler for profiling your
application code?

Salah satu keunggulan utamanya adalah lebih cepat mencari tahu kelemahan program dan apa yang bisa diperbaiki, selain itu saya juga bisa menyimulasikan seberapa cepat program saya berjalan dalam kondisi tertentu.

6. How do you handle situations where the results from profiling with IntelliJ Profiler are
not entirely consistent with findings from performance testing using JMeter?

Sejauh ini saya tidak merasakan hal tersebut, karena seluruh hasil tes saya ketika dites dalam IntelliJ Profiler dan Jmeter konsisten. Sebelum refactor cukup lambat, namun setelah refactor lebih cepat, dan sebaliknya. 
Namun, dalam kasus IntelliJ Profiler berbeda dengan Jmeter, saya harus mengecek ulang program saya ketika dites dan melihat jika ada perubahan yang saya tidak sadari yang memengaruhi tes.

7. What strategies do you implement in optimizing application code after analyzing results
from performance testing and profiling? How do you ensure the changes you make do
not affect the application's functionality?

Saya memastikan perubahan yang saya lakukan tidak memengaruhi program secara keseluruhan dengan mengetes ide-ide yang saya temukan terlebih dahulu. Saya mencari metode yang mirip dengan kode aslinya, serta cara-cara
men-simplifikasinya di internet. Saya juga melihat contoh seperti di Stackoverflow, Geeksforgeeks, Baeldung, dan lain-lain untuk mencari inspirasi dalam mengubah kode saya.
