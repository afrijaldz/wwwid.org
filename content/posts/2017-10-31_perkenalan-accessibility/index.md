---
title: "Perkenalan Accessibility"
author: "Satya Kresna Adi Pratama"
date: 2017-10-31T00:11:45.428Z
lastmod: 2019-05-20T16:26:27+07:00
featured: true
description: ""

subtitle: "Sebagai seorang web developer, selain urusan performance dan interface pada website yang dibuat, kita perlu memperhatikan siapa user kita…"
tags:
 - Accessibility 
 - Web Accessibilty 
 - WCAG 
 - People With Disabilities 
 - Billion Users On The Web 

image: "/posts/2017-10-31_perkenalan-accessibility/images/1.png" 
images:
 - "/posts/2017-10-31_perkenalan-accessibility/images/1.png" 


aliases:
    - "/perkenalan-accessibility-c9d893318567"
---

![image](/posts/2017-10-31_perkenalan-accessibility/images/1.png)



Sebagai seorang web developer, selain urusan performance dan interface pada website yang dibuat, kita perlu memperhatikan siapa user kita. Apakah user kita lahir tidak ada kekurangan fisik atau sebaliknya (disabilitas). Jika user yang mengakses website kita adalah kalangan disabiilitas maka kita perlu memberikan perhatian ekstra terhadap website kita. Lalu bagaimana caranya? Accessibility adalah jawaban dari hal tersebut.

## **Definisi**

Accessibility secara garis besar adalah bagaimana user yang disabilitas bisa mengakses aplikasi kita layaknya orang normal (_making disability users able to access our website_). Accessibility sering disingkat dengan a11y layaknya localization (l10n) dan intenationalization (i18n). Dengan bantuan teknologi pembantu (assitive technology) seperti screen reader dan mengubah website kita ke arah a11y maka orang disabilitas bisa mengakses website kita layaknya orang normal.

> Perlu dipahami bahwa a11y bukanlah sebuah fitur tetapi sebuah kebutuhan bahkan keharusan (It’s not a feature but a requirement even must)

## **Tools untuk Accessibility**

Saya akan menggunakan Lighthouse yang ada pada Chrome browser untuk menganalisa apakah website kita sudah bisa dikatakan Accessibility. Kita akan bahas dipertemuan selanjutnya.

## **Panduan mempelajari Accessibility**

1. [WebAIM WCAG 2.0 Checklist](https://webaim.org/standards/wcag/checklist).

2. [Web Content Accessibility Guidelines](https://www.w3.org/WAI/WCAG20/quickref/).

3. [Udacity — Web Accessibility](https://classroom.udacity.com/courses/ud891).

## **Kriteria Accessibility**

1. **Perceivable** (Konten website tersedia bagi indera — penglihatan, pendengaran dan atau sentuhan).

2. **Operable** (Tampilan form, kendali dan navigasi dapat dioperasikan).

3. **Understandable** (Konten dan tampilan dapat dimengerti).

4. **Robust** (Konten dapat digunakan dengan baik oleh berbagai platform termasuk teknologi bantu).

Kita sebut dengan _POUR_

## **Alasan membuat konten Accessibility dalam bahasa Indonesia**

1. Merupakan kesempatan bagi saya untuk memperkenalkan konten Accessibility dalam bahasa Indonesia. _Sejauh yang saya lihat di forum komunitas web developer belum ada yang membahas tentang hal ini apalagi dalam konten bahasa Indonesia._ Masih ada beberapa orang yang belum bisa mencerna sebuah materi dengan baik dengan bahasa Inggris maka dari itulah saya membuatkan artikel Accessibility dalam bahasa Indonesia.

2. Menurut sudut pandang saya rata-rata web developer jauh lebih mempentingkan performance website dibandingkan Accessibility. Tetapi, perlu dipahami bahwa kita harus tahu siapa user kita. Apakah mereka lahir tanpa cacat fisik atau sebaliknya (disabilitas). Sehingga Accessibility wajib ada disetiap website. **Accessibility adalah prioritas utama anda jika anda ingin mencapai** [**billion users on the web**](https://developers.google.com/web/billions/)**.**

Di bagian selanjutnya saya akan menjelaskan implementasi Accessibility di dunia web.
