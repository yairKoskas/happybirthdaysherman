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
&#x202b;
אתה אחד האנשים החכמים שאני מכיר, תמיד כיף ממש לדבר איתך
תישאר כמו שאתה אח יקר.
> יהונתן ליפשיץ

&#x202b;
מזל דוב שרמן!!!  
&#x202b;
אתה חבר טוב ותמיד כיף להיות איתך ולדבר איתך. אתה מצחיק ותמיד מלא שמחת חיים (חוץ מאחרי מייל מקמינקא), ואני ממש שמח ללמוד איתך. מאחל לך הרבה בריאות ואושר.  
&#x202b;
אוהב,   
![bear](bear_ido.jpeg)   
> עדו

&#x202b;
שרמן אח יקר, מזל טוב שיהיה לך, תמשיך להיות מי שאתה (לאכול קליק אדום ולחבק עמודים), שתחייה באושר בעושר ובהושר עד עצם היום הזה, ועד עצם היום הבא והבא (עד 120 קיצר). מזל טוב!
>  יואב נפתלי

&#x202b;
מזל טוב שרמן, מקווה שנהנת מהctf למרות שלא יצא לי לתרום לו ממש
> יהונתן חרמץ

&#x202b;
שרמן שרמן, חברי הטוב לקליק האדום ולwitcher 3. מזל טוב על 18, עכשיו באופן חוקי אתה יכול לעשות שוטים של קליק עם וודקה (לא שיש לי ספק שאתה לא עושה את זה עכשיו, כי אתה רוסי וזה. בלי להיות גזען כמובן). אז הגעת לגיל המצוות וזה בר מצווה וזה. תמשיך לחבק עמודים,
מחברך הטוב,  
> אופיר

&#x202b;
שרמי חברצ יקר שלי, מלא מלא מזל טוב, אוהבת מלאאא🖤🦆
> ספיר

&#x202b;
לרון היקר הרבה מזל טוב ליום הולדתך
&#x202b;   
מאחל לך להמשיך להיות תותח בקורסים ובן אדם אדיב ונחמד שאני מחבב מאוד
&#x202b;  
דבר איתי אם בא לך קליק🤤 
&#x202b;
תמשיך לחבק עמודים🙃 
> שחר מאיר

&#x202b;
מזל טוב אתה אחלה ילד תמשיך להיות אחלה בחלה ותהנה מהחיים ומהלימודים. בהצלחה בהמשך התואר.
> טל "אדוני" נקר

&#x202b;
שרמן המלךךךךך👑😍  
&#x202b;
מזל טוב ליומו🥳🥳🥳  
&#x202b;
עד 0️⃣2️⃣1️⃣ (בהקסה כמובן)  
&#x202b;
שתמשיך לפרק CTFs כמו שפירקת את זה (אם לא הצלחת אתה לא אמור לקרוא את זה עכשיו, לא?🤔)  
&#x202b;
שתמשיך להיות אחראי הקורס הכי טוב שיש (חוץ ממני כמובן😌)  
&#x202b;
תמשיך להיות יותר חכם מהבינה המלאכותית שאתה יוצר (קח את זה כמחמאה, לא בכיוון ההפוך נו) 🤓  
&#x202b;
ותזכיר לי לקנות לך קליק אדום כשחוזרים 🍫 (איך אין אימוג'י לקליק?)  
&#x202b;
אוהב❤️❤️❤️   
> עמית   
> הבן   
> מילוא   
> לא ניר   
> הבנת קיצר

------

## Write up

At first you needed to extract Omri's file from the given image using `binwalk`. The zip file was concatenated using simple python code to the image.

*Omri please add a write up*

Than you have reached Tal's challange - thousands upon thousands of files and directories. The correct file was at the directories `2/3/4/2/0/0/2/`! In all the other files you had random lines from random wikipidia values.

But the file content was weird, it was [brainfuck](https://en.wikipedia.org/wiki/Brainfuck), the result was a clue for you to go to the Dr' Erez Shiner class מבנים אלגבריים lecure 7 about RSA.

There you needed to notice that `N` was to small for RSA so you can break it to `p` and `q` using [Integer factorization calculator](https://www.alpertron.com.ar/ECM.HTM).

And here you are!

------
### יוצרי האתגרים

אתגר | יוצרים
-----|-----
רעיון | מילוא
Image | ליפשיץ
Reversing | עומרי
Misc | טל
Rsa | עמית ניר
אתר | ליפשיץ
