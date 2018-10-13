---
title: While Loop
localeTitle: حائط اللوب
---

تقوم حلقة while بتنفيذ كتلة من التعليمة البرمجية حتى يكون الشرط المحدد خاطئًا. نظرًا لأن اختبار التعبير "while" يحدث قبل كل تنفيذ للحلقة ، فإن حلقة while تنفذ صفراً أو أكثر. يختلف هذا عن حلقة do ، التي تنفذ مرة واحدة أو أكثر لأن اختبار التعبير يحدث بعد تنفيذ الحلقة. 1

## مثال

 `int i = 0; 
 while (i < 5) 
 { 
    Console.WriteLine("Number " + i); 
    i++; 
 } 
` 

### انتاج:

 `> Number 0 
 > Number 1 
 > Number 2 
 > Number 3 
 > Number 4 
` 

## استخدامات اخرى

غالباً ما يتم استخدام الحلقات while لإفرازات لا نهائية باستخدام (على سبيل المثال) `while (true)` ، فقط أن تنتهي من خلال شرط لا يرتبط بالشرط الأولي للحلقة.

 `int i = 0; 
 while (true) 
 { 
    if(i<50){ 
        Console.WriteLine("Number " + i); 
        i++; 
    } 
    else{ 
        Console.WriteLine("End of loop"); 
        break; 
    } 
 } 
` 

## الخلافات إلى `for` حلقة

أكبر الاختلافات بين `for` و `while` الحلقات هي أن `while` يستخدم عادة عندما مطور غير متأكد من العدد الدقيق للتكرار من حلقة، و `for` يستخدم عندما يكون من الواضح كم عدد مرات تكرار خلال التعليمات البرمجية.

### مصادر

*   [مايكروسوفت ج # - بينما](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/while)