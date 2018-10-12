---
title: Match Literal Strings
localeTitle: المباراة الحرفيه الاوتار
---
## المباراة الحرفيه الاوتار

هذا التحدي لا يختلف عن السابق. في هذه الحالة ، أنت تعلم أن حرفية السلسلة تكون حساسة لحالة الأحرف. وهذا يعني أنه عندما تختبر لمعرفة ما إذا كانت السلسلة تحتوي على حرفي ، فستبحث عن الحالة الدقيقة (السفلية أو العلوية) داخل السلسلة. سوف تتعلم كيفية العثور على حرفية سلسلة بغض النظر عن حالتهم ، في درس قادم.

في هذا التحدي ، كنت تجد والدو ... داخل سلسلة!

## تلميح 1:

تغيير الخط لجعل السلسلة الصحيحة حرفية.

## تنبيه المفسد - الحل إلى الأمام!

## حل:

 `let waldoIsHiding = "Somewhere Waldo is hiding in this text."; 
 let waldoRegex = /Waldo/; // Change this line 
 let result = waldoRegex.test(waldoIsHiding); 
`