# מזל טוב שרמןןןןן

&#x202b;
[מזל טוב מקמינקא!!](WhatsApp Video 2020-04-22 at 15.51.05.mp4)

&#x202b;
מזל טוב שרמן!!! 18 זה לא צחוק😝 תמשיך להיות חבר טוב ובן אדם שכיף להיות איתו. חוץ מזה נאחל לך חיים מאושרים, בעז"ה תאכל עוד הרבה קליק אדום ותצליח להתמודד עם קמינקא😂
&#x202b;
מזל טוב אחי🎉🎊🥳
> יואב סימן טוב

&#x202b;
מזל טוב שרמן יצעיר! שתצליח בכל מה שתרצה, בצופים, באוניברסיטה, בבית ספר... שתמיד יהיה לך כיף וקל בכל מה שתעשה ותמיד תהיה מוקף באנשים אהובים
> יואב כרמל

&#x202b;
שרמן,
אתה בין בני האדם החכמים, מצחיקים, מוכשרים, שותפים נהדרים למתקדם, וטובים בctf שאני מכירה! תמשיך להיות מי שאתה לנצח ואל תשתנה לעולם. מבטיחה לקנות לך קליק אדום שנצא. 
&#x202b;
ומקווה שנהנית מהctf!!!
> עמית ניר

&#x202b;
מזל טוב שרמן!!
אתה אחד האנשים החכמים שאני מכיר, תמיד כיף ממש לדבר איתך
תישאר כמו שאתה אח יקר.
> יהונתן ליפשיץ

&#x202b;
מזל טוב שרמן, מקווה שנהנת מהctf למרות שלא יצא לי לתרום לו ממש
> יהונתן חרמץ

&#x202b;
מזל טוב אתה אחלה ילד תמשיך להיות אחלה בחלה ותהנה מהחיים ומהלימודים. בהצלחה בהמשך התואר.
> טל "אדוני" נקר

------

## Write up

At first you needed to extract Omri's file from the given image using `binwalk`. The zip file was concatenated using simple python code to the image.

*Omri please add a write up*

Than you have reached Tal's challange - thousands upon thousands of files and directory. The correct file was at the directories `2/3/4/2/0/0/2/`! In all the other files you had random lines from random wikipidia values.

But the file content was weird, it was [brainfuck](https://en.wikipedia.org/wiki/Brainfuck), the result was a clue for you to go to the Dr' Erez Shiner class מבנים אלגבריים lecure 7 about RSA.

There you needed to notice that `N` was to small for RSA so you can break it to `p` and `q` using [Integer factorization calculator](https://www.alpertron.com.ar/ECM.HTM).

And here you are!

------
### יוצרי האתגרים

אתגר | יוצרים
-----|-----
Image | ליפשיץ
Reversing | עומרי
Misc | טל
Rsa | עמית
אתר | ליפשיץ
