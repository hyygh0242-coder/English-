# English-
English group 
<!DOCTYPE html>
<html lang="uz">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#071426">
<meta name="description" content="My English Group — ingliz tilini o‘rganish, grammatik mavzular va testlar platformasi.">
<title>My English Group</title>
<style>
:root{--bg:#06101f;--panel:#0d1d33;--panel2:#122743;--blue:#1677d2;--cyan:#53b8ff;--red:#e63950;--white:#f5f8ff;--muted:#a9bad0;--line:#263e5d}
*{box-sizing:border-box}
body{margin:0;background:radial-gradient(circle at 15% 0%,#102b4a 0,transparent 35%),var(--bg);color:var(--white);font-family:Arial,sans-serif;min-height:100vh}
button,input{font:inherit}button{cursor:pointer;border:0;border-radius:10px;padding:12px 16px;font-weight:700;transition:.2s}
button:active{transform:scale(.98)}
.blue{background:linear-gradient(135deg,#1688ed,#0756a7);color:white}
.red{background:linear-gradient(135deg,#f04b60,#b91f38);color:white}
.dark{background:#1a304c;color:white;border:1px solid #365170}
.white{background:#f5f8ff;color:#071426}
.hidden{display:none!important}
.container{max-width:1120px;margin:auto;padding:14px}
#welcome{max-width:1000px;margin:0 auto;padding:18px}
.welcome-card{overflow:hidden;border:1px solid #294765;border-radius:22px;background:#0d1d33;box-shadow:0 20px 65px #0008}
.welcome-image{height:clamp(250px,48vw,490px);position:relative;background:#10243c}
.welcome-image img{width:100%;height:100%;object-fit:cover;display:block}
.welcome-image:after{content:"";position:absolute;inset:0;background:linear-gradient(0deg,#06101fbb,transparent 70%)}
.welcome-caption{text-align:center;padding:20px 16px 24px}
.welcome-caption h1{font-size:clamp(27px,5vw,43px);letter-spacing:2px;margin:0 0 8px}
.welcome-caption h1 span{color:var(--cyan)}
.welcome-caption p{color:var(--muted);margin:0 0 20px}
.welcome-actions{display:flex;justify-content:center;gap:12px;flex-wrap:wrap}
.welcome-actions button{min-width:145px}
.upload-label{display:inline-flex;align-items:center;justify-content:center;background:#174d7e;color:#fff;padding:10px 13px;border-radius:9px;margin-top:10px;font-size:12px;font-weight:bold;cursor:pointer}
.upload-label input{display:none}
.welcome-upload{margin-top:0}
header{display:flex;align-items:center;justify-content:space-between;gap:12px;padding:14px 0;border-bottom:1px solid var(--line)}
.logo{font-weight:900;font-size:21px;letter-spacing:.5px}.logo span{color:var(--red)}
.topnav{display:flex;gap:8px;flex-wrap:wrap;margin:13px 0 20px}
.topnav button{padding:10px 13px;font-size:13px}
.title{font-size:22px;margin:22px 0 13px}
.subtitle{color:var(--muted);font-size:14px;line-height:1.6}
.grid{display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:11px}
.section{background:linear-gradient(145deg,#122743,#0d1d33);border:1px solid #294563;border-radius:13px;padding:15px;min-height:105px;cursor:pointer;transition:.2s}
.section:hover{border-color:var(--cyan);transform:translateY(-2px)}
.section b{font-size:14px}.section p{font-size:12px;color:var(--muted);margin:8px 0 0}
.number{font-size:11px;color:#ff7182;margin-bottom:8px;font-weight:bold}
.card{background:linear-gradient(145deg,#10233c,#0b192c);border:1px solid var(--line);padding:16px;border-radius:14px;margin:13px 0}
.progress{height:9px;background:#263b56;border-radius:20px;overflow:hidden}.progress span{display:block;height:100%;width:0;background:linear-gradient(90deg,var(--blue),var(--red));transition:.3s}
.photos{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:13px}
.photo{height:220px;border-radius:14px;overflow:hidden;background:#13243a;border:1px solid #304968}
.photo img{width:100%;height:100%;object-fit:cover;display:block}
.photo-actions{display:flex;gap:7px;flex-wrap:wrap}
input[type=text],input[type=search]{width:100%;padding:13px;border-radius:9px;border:1px solid #355170;background:#09172a;color:white;margin:10px 0;outline:none}
.rule{background:#123451;padding:15px;border-left:4px solid var(--blue);border-radius:9px;line-height:1.8}
.formula{background:#3a1c2a;padding:15px;border-left:4px solid var(--red);border-radius:9px;line-height:1.8}
.example{background:#0b192c;border:1px solid #29415f;padding:12px;border-radius:9px;margin:8px 0;line-height:1.7}
.option{display:block;width:100%;text-align:left;background:#203753;color:white;margin:8px 0;border:1px solid #3b5573}
.option.selected{background:#174c78;border-color:#58baff}.option.correct{background:#17623e}.option.wrong{background:#782c36}
.muted{color:var(--muted);font-size:13px}.actions{display:flex;gap:8px;flex-wrap:wrap}
.badge{display:inline-block;background:#173b5e;color:#9ed7ff;border-radius:20px;padding:5px 9px;font-size:11px}
footer{text-align:center;color:#8298b4;padding:25px 10px;font-size:12px}
@media(max-width:700px){.grid{grid-template-columns:repeat(2,minmax(0,1fr))}.photos{grid-template-columns:1fr}.photo{height:230px}.logo{font-size:17px}.topnav button{flex:1}.container{padding:12px}}
@media(min-width:701px) and (max-width:900px){.grid{grid-template-columns:repeat(3,minmax(0,1fr))}}
</style>
</head>
<body>

<!-- KIRISH OYNASI -->
<section id="welcome" class="container">
 <div class="welcome-card">
  <div class="welcome-image">
   <img id="welcomeImage" src="https://images.unsplash.com/photo-1503676260728-1c00da094a0b?w=1400" alt="Ingliz tili darsi">
  </div>
  <div class="welcome-caption">
   <h1>MY <span>ENGLISH</span> GROUP</h1>
   <p>Ingliz tilini oson, tartibli va qiziqarli o‘rganing</p>
   <div class="welcome-actions">
    <button class="blue" onclick="enterSite()">KIRISH</button>
    <button class="red" onclick="leaveSite()">CHIQISH</button>
   </div>
   <label class="upload-label welcome-upload">Kirish rasmini almashtirish
    <input type="file" accept="image/*" onchange="uploadPhoto(event,'welcomeImage','welcome')">
   </label>
  </div>
 </div>
</section>

<!-- ASOSIY SAYT -->
<main id="app" class="container hidden">
<header>
 <div class="logo">MY ENGLISH <span>GROUP</span></div>
 <button class="red" onclick="leaveSite()">CHIQISH</button>
</header>
<nav class="topnav">
 <button class="blue" onclick="homePage()">BOSH SAHIFA</button>
 <button class="dark" onclick="topicsPage()">MAVZULAR</button>
 <button class="dark" onclick="testPage()">TESTLAR</button>
 <button class="dark" onclick="resultsPage()">NATIJALAR</button>
</nav>

<section id="homePage">
 <h2 class="title">O‘RGANISH MARKAZI</h2>
 <p class="subtitle">Kerakli bo‘limni tanlang va ingliz tilini bosqichma-bosqich o‘rganing.</p>
 <div class="grid">
  <div class="section" onclick="topicsPage()"><div class="number">01 · TA’LIM</div><b>📘 GRAMMATIKA</b><p>130 ta ingliz tili mavzusi</p></div>
  <div class="section" onclick="testPage()"><div class="number">02 · AMALIYOT</div><b>📝 TESTLAR</b><p>Oson, o‘rta va qiyin daraja</p></div>
  <div class="section" onclick="resultsPage()"><div class="number">03 · NAZORAT</div><b>🏆 NATIJALAR</b><p>O‘zlashtirish va test tarixi</p></div>
  <div class="section" onclick="topicsPage()"><div class="number">04 · BILIM</div><b>🎓 DARS MASHG‘ULOTLARI</b><p>Qoida, formula va misollar</p></div>
 </div>
 <div class="card">
  <b>MENING O‘ZLASHTIRISHIM</b>
  <p id="progressText" class="muted">0 / 130 ta mavzu</p>
  <div class="progress"><span id="progressBar"></span></div>
 </div>
 <h2 class="title">GALEREYA</h2>
 <p class="subtitle">Rasmlarni telefon galereyasidan tanlab almashtirishingiz mumkin.</p>
 <div class="photos">
  <div><div class="photo"><img id="photo1" src="https://images.unsplash.com/photo-1509062522246-3755977927d7?w=800" alt="Sinf xonasi"></div><label class="upload-label">＋ RASM TANLASH<input type="file" accept="image/*" onchange="uploadPhoto(event,'photo1','photo1')"></label></div>
  <div><div class="photo"><img id="photo2" src="https://images.unsplash.com/photo-1456513080510-7bf3a84b82f8?w=800" alt="Kitoblar"></div><label class="upload-label">＋ RASM TANLASH<input type="file" accept="image/*" onchange="uploadPhoto(event,'photo2','photo2')"></label></div>
  <div><div class="photo"><img id="photo3" src="https://images.unsplash.com/photo-1434030216411-0b793f4b4173?w=800" alt="O‘qish jarayoni"></div><label class="upload-label">＋ RASM TANLASH<input type="file" accept="image/*" onchange="uploadPhoto(event,'photo3','photo3')"></label></div>
 </div>
</section>

<section id="topicsPage" class="hidden">
 <button class="dark" onclick="homePage()">← BOSH SAHIFA</button>
 <h2 class="title">INGLIZ TILI MAVZULARI</h2>
 <input id="search" type="search" placeholder="Mavzuni qidirish..." oninput="renderTopics()">
 <div id="topicList" class="grid"></div>
</section>

<section id="lessonPage" class="hidden">
 <button class="dark" onclick="topicsPage()">← MAVZULAR</button>
 <div class="card">
  <span class="badge" id="lessonLevel"></span>
  <h2 id="lessonTitle"></h2>
  <p class="muted" id="lessonDescription"></p>
  <h3>📌 GRAMMATIK QOIDA</h3><div class="rule" id="lessonRule"></div>
  <h3>🧩 FORMULA</h3><div class="formula" id="lessonFormula"></div>
  <h3>✍️ MISOLLAR</h3><div id="lessonExamples"></div>
  <h3>💡 ESLAB QOLING</h3><div class="example" id="lessonTip"></div>
  <button class="blue" style="width:100%;margin-top:15px" onclick="lessonTest()">MAVZU TESTINI BOSHLASH →</button>
 </div>
</section>

<section id="lessonQuizPage" class="hidden">
 <button class="dark" onclick="showLesson()">← DARS</button>
 <div class="card"><h2 id="lessonQuizTitle"></h2><p class="muted">Savollar ingliz tilida beriladi.</p>
  <div id="lessonQuestions"></div>
  <button class="blue" onclick="gradeLesson()">JAVOBLARNI TEKSHIRISH</button>
  <div id="lessonResult" class="hidden"></div>
 </div>
</section>

<section id="testPage" class="hidden">
 <button class="dark" onclick="homePage()">← BOSH SAHIFA</button>
 <h2 class="title">UMUMIY INGLIZ TILI TESTI</h2>
 <div class="card"><p class="muted">O‘zingizga mos darajani tanlang. Har bir testda 30 ta savol bor.</p>
  <div class="grid">
   <button class="blue" onclick="startGeneral('easy')">OSON</button>
   <button class="white" onclick="startGeneral('medium')">O‘RTA</button>
   <button class="red" onclick="startGeneral('hard')">QIYIN</button>
  </div>
 </div>
 <div id="generalQuiz" class="hidden card">
  <h2 id="generalTitle"></h2><p id="questionCounter" class="muted"></p>
  <div class="progress"><span id="quizProgress"></span></div>
  <div id="generalQuestions"></div>
  <button class="blue" onclick="finishGeneral()">TESTNI YAKUNLASH</button>
  <div id="generalResult" class="hidden card"></div>
 </div>
</section>

<section id="resultsPage" class="hidden">
 <button class="dark" onclick="homePage()">← BOSH SAHIFA</button>
 <h2 class="title">MENING NATIJALARIM 🏆</h2>
 <div class="card"><h3>Tugatilgan mavzular</h3><h1 id="doneCount">0</h1></div>
 <div class="card"><h3>Testlar tarixi</h3><div id="savedResults"></div></div>
</section>
<footer>MY ENGLISH GROUP © 2026 · BARCHA HUQUQLAR HIMOYALANGAN</footer>
</main>

<script>
// 130 TA MAVZU
const groups=[
["BOSHLANG‘ICH",["Subject Pronouns","Verb To Be: Am / Is / Are","Verb To Be: Negative","Verb To Be: Questions","Possessive Adjectives","Possessive Pronouns","A / An Articles","The Article","Singular and Plural Nouns","This / That / These / Those"]],
["ELEMENTARY",["Present Simple: Positive","Present Simple: Negative","Present Simple: Questions","Present Simple: He / She / It","Adverbs of Frequency","Present Continuous: Positive","Present Continuous: Negative","Present Continuous: Questions","Present Simple or Continuous","Imperatives"]],
["O‘TGAN ZAMONLAR",["Past Simple: Regular Verbs","Past Simple: Irregular Verbs","Past Simple: Negative","Past Simple: Questions","Was / Were","Past Continuous","Past Simple or Past Continuous","There Is / There Are","There Was / There Were","Have Got / Has Got"]],
["PERFECT ZAMONLAR",["Present Perfect","Present Perfect: Ever / Never","Just / Already / Yet","For and Since","Present Perfect or Past Simple","Present Perfect Continuous","Past Perfect","Past Perfect and Past Simple","Used To","Would for Past Habits"]],
["KELASI ZAMONLAR",["Future Simple: Will","Be Going To","Present Continuous for Future","Present Simple for Timetables","Will or Going To","Future Continuous","Future Perfect","Future Perfect Continuous","First Conditional","Second Conditional"]],
["SHART GAPLAR",["Third Conditional","Mixed Conditionals","Unless","As Long As","Wish + Past Simple","Wish + Past Perfect","Would Rather","Had Better","If I Were You","Conditional Review"]],
["MODAL FE’LLAR",["Can and Could","May and Might","Must and Have To","Should and Ought To","Mustn't and Don't Have To","Need To and Needn't","Could Have Done","Should Have Done","Must Have Done","Be Able To"]],
["OT VA OLMOSHLAR",["Countable and Uncountable Nouns","Much and Many","A Lot Of","Few and Little","Some and Any","No and None","Each and Every","All and Most","Both / Either / Neither","Reflexive Pronouns"]],
["SIFATLAR",["Adjective Order","Adverbs of Manner","Comparative Adjectives","Superlative Adjectives","As ... As","Too and Enough","So and Such","-ED and -ING Adjectives","Adjectives or Adverbs","Adjective + Preposition"]],
["PREDLOGLAR",["Prepositions of Time","Prepositions of Place","Prepositions of Movement","By / Until / During / For","Before and After","In / On / At","Verb + Preposition","Adjective + Preposition","Noun + Preposition","Preposition Review"]],
["MAJHUL NISBAT VA KO‘CHIRMA GAP",["Passive Voice: Present","Passive Voice: Past","Passive Voice: Future","Passive with Modals","Have Something Done","Reported Statements","Reported Questions","Reported Commands","Say and Tell","Relative Clauses"]],
["ILG‘OR GRAMMATIKA",["Defining Relative Clauses","Non-defining Relative Clauses","Question Tags","Indirect Questions","Gerunds and Infinitives","Verb + ING","Verb + To Infinitive","Advanced Articles","Linking Words","Although / Despite"]],
["QO‘SHIMCHA MAVZULAR",["Question Words","Subject and Object Questions","Word Order","Too / Also / Either","Both / Neither","So Do I / Neither Do I","Make and Do","Get and Have","Phrasal Verbs","Common Collocations"]]
];

const topics=[];
groups.forEach((g,gi)=>g[1].forEach(name=>topics.push({id:topics.length,name,group:g[0],groupId:gi})));

let done=JSON.parse(localStorage.getItem("meg_done")||"[]"),
currentTopic=0,lessonAnswers={},currentLessonQuestions=[],
generalAnswers={},generalQuestions=[],generalLevel="";

const lessonData=[
{rule:"Subject pronouns gapda ish-harakatni bajaruvchi shaxs yoki narsani bildiradi. To be fe’li shaxsga qarab o‘zgaradi.",formula:"I + am | He / She / It + is | You / We / They + are",examples:["I am a student. — Men o‘quvchiman.","She is happy. — U xursand.","They are friends. — Ular do‘stlar."],tip:"I bilan AM, he/she/it bilan IS, you/we/they bilan ARE ishlatiladi."},
{rule:"Present Simple odatlar, kundalik ishlar va umumiy haqiqatlarni bildiradi.",formula:"(+) S + V1(s/es) | (-) S + do/does not + V1 | (?) Do/Does + S + V1?",examples:["I play football every day. — Men har kuni futbol o‘ynayman.","She goes to school. — U maktabga boradi.","He doesn't like coffee. — U qahvani yoqtirmaydi."],tip:"He, she, it bilan tasdiq gapda fe’lga -s yoki -es qo‘shiladi."},
{rule:"Present Continuous hozir davom etayotgan ish-harakatni bildiradi.",formula:"S + am / is / are + V-ing",examples:["I am reading now. — Men hozir o‘qiyapman.","She is cooking. — U ovqat tayyorlayapti.","They are playing. — Ular o‘ynashyapti."],tip:"Now va at the moment iboralari ko‘p ishlatiladi."},
{rule:"Past Simple o‘tmishda boshlangan va tugagan ish-harakat uchun ishlatiladi.",formula:"(+) S + V2 | (-) S + did not + V1 | (?) Did + S + V1?",examples:["I visited London. — Men Londonga bordim.","She bought a book. — U kitob sotib oldi.","Did you see him? — Uni ko‘rdingmi?"],tip:"Did dan keyin fe’l doimo V1 shaklida keladi."},
{rule:"Present Perfect o‘tmishdagi ishning hozirgi natijasi yoki hayotiy tajribani bildiradi.",formula:"S + have / has + V3",examples:["I have finished my homework. — Uy vazifamni tugatdim.","She has visited London. — U Londonda bo‘lgan.","We have never seen it. — Biz buni hech ko‘rmaganmiz."],tip:"Have: I/you/we/they bilan; has: he/she/it bilan."},
{rule:"Future Simple kelajakdagi ish, va’da va taxminlarni ifodalaydi.",formula:"S + will + V1",examples:["I will help you. — Men senga yordam beraman.","She will come tomorrow. — U ertaga keladi.","They will study. — Ular o‘qishadi."],tip:"Will dan keyin fe’lning birinchi shakli keladi."},
{rule:"Conditional gaplar shart va uning natijasini ifodalaydi.",formula:"First: If + Present Simple, will + V1. Second: If + Past Simple, would + V1.",examples:["If it rains, I will stay home. — Yomg‘ir yog‘sa, uyda qolaman.","If I were rich, I would travel. — Boy bo‘lganimda sayohat qilardim."],tip:"First Conditional ning if qismida odatda will ishlatilmaydi."},
{rule:"Modal verbs qobiliyat, maslahat, ruxsat va majburiyatni bildiradi.",formula:"S + can / could / should / must + V1",examples:["I can swim. — Men suza olaman.","You should study. — Sen o‘qishing kerak.","You must listen. — Sen tinglashing shart."],tip:"Modal fe’llardan keyin asosiy fe’l to qo‘shimchasiz keladi."},
{rule:"Otlar sanaladigan va sanalmaydigan bo‘ladi. Miqdor bildiruvchi so‘zlar ot turiga qarab tanlanadi.",formula:"Many + countable nouns | Much + uncountable nouns",examples:["How many books? — Nechta kitob?","How much water? — Qancha suv?","I have some friends. — Mening bir nechta do‘stim bor."],tip:"Information, advice va water sanalmaydigan otlardir."},
{rule:"Adjectives otni, adverbs esa fe’l yoki harakatni tasvirlaydi. Sifatlar taqqoslashda ham ishlatiladi.",formula:"Adjective: beautiful | Adverb: beautifully | Comparative: bigger than",examples:["She is beautiful. — U chiroyli.","She sings beautifully. — U chiroyli kuylaydi.","Ali is taller than Vali. — Ali Validan balandroq."],tip:"Than taqqoslashda, the esa orttirma darajada ishlatiladi."},
{rule:"Prepositions vaqt, joy va harakat yo‘nalishini bildiradi.",formula:"AT = aniq vaqt | ON = kun va sanalar | IN = oy, yil va katta joylar",examples:["I wake up at 7. — Men soat 7 da uyg‘onaman.","I study on Monday. — Men dushanba kuni o‘qiyman.","I was born in 2012. — Men 2012-yilda tug‘ilganman."],tip:"At 7, on Monday, in July."},
{rule:"Passive Voice gapda ishni kim bajarganidan ko‘ra, ish-harakatning o‘ziga urg‘u beradi.",formula:"BE + V3",examples:["The room is cleaned. — Xona tozalanadi.","The letter was written. — Xat yozildi.","English is spoken worldwide. — Ingliz tilida butun dunyoda gaplashiladi."],tip:"Zamonga mos BE shakli va fe’lning V3 shakli ishlatiladi."},
{rule:"Bu bo‘lim savol tuzish, so‘z tartibi va kundalik inglizcha iboralarni o‘rgatadi.",formula:"Question word + auxiliary + subject + verb?",examples:["What is your name? — Isming nima?","Where do you live? — Qayerda yashaysan?","How often do you study? — Qanchalik tez-tez o‘qiysan?"],tip:"Ingliz tilida gapdagi so‘z tartibiga e’tibor bering."}
];

const lessonBanks=[
[["I ___ a student.",["am","is","are"],0],["She ___ happy.",["am","is","are"],1],["They ___ friends.",["is","am","are"],2],["___ he a teacher?",["Are","Is","Am"],1],["We ___ students.",["am","are","is"],1]],
[["She ___ to school every day.",["go","goes","going"],1],["I ___ football.",["plays","playing","play"],2],["He doesn't ___ tea.",["likes","like","liking"],1],["___ you speak English?",["Do","Does","Are"],0],["They ___ TV every day.",["watch","watches","watching"],0]],
[["I ___ reading now.",["am","is","are"],0],["She is ___ food.",["cook","cooks","cooking"],2],["They ___ playing.",["is","are","am"],1],["He isn't ___.",["sleep","sleeps","sleeping"],2],["Are you ___?",["study","studying","studies"],1]],
[["I ___ him yesterday.",["see","saw","seen"],1],["She ___ a book.",["buy","buys","bought"],2],["Did you ___ it?",["saw","see","seen"],1],["They ___ at home.",["was","were","is"],1],["He didn't ___.",["came","comes","come"],2]],
[["I have ___ my work.",["finish","finished","finishing"],1],["She ___ visited Paris.",["have","has","is"],1],["Have you ever ___ London?",["visit","visited","visiting"],1],["I have lived here ___ 2020.",["for","since","at"],1],["They have ___ arrived.",["just","yet","ago"],0]],
[["I ___ call you.",["will","am","did"],0],["She is going to ___.",["travel","travels","traveling"],0],["He ___ come tomorrow.",["will","was","does"],0],["We ___ study tonight.",["are going to","going","is going"],0],["I think it ___ rain.",["will","was","did"],0]],
[["If it rains, I ___ stay home.",["will","would","did"],0],["If I were rich, I ___ travel.",["will","would","am"],1],["If she studies, she ___ pass.",["will","would","was"],0],["I wish I ___ taller.",["am","were","be"],1],["Unless means:",["if not","because","when"],0]],
[["I ___ swim.",["can","cans","am can"],0],["You ___ study more.",["should","should to","shoulds"],0],["She ___ speak English.",["can","cans","canning"],0],["You ___ smoke here.",["mustn't","must","should"],0],["He ___ be at home.",["might","might to","mights"],0]],
[["How ___ books?",["much","many","little"],1],["How ___ water?",["many","much","few"],1],["I need ___ information.",["a","an","some"],2],["___ of them are students.",["Both","Every","Much"],0],["This book is ___.",["my","mine","me"],1]],
[["Ali is ___ than Vali.",["tall","taller","tallest"],1],["She sings ___.",["beautiful","beautifully","beauty"],1],["This is the ___ house.",["big","bigger","biggest"],2],["He is as ___ as me.",["tall","taller","tallest"],0],["The film was ___.",["boring","bored","bore"],0]],
[["I wake up ___ 7.",["in","on","at"],2],["I was born ___ 2012.",["at","on","in"],2],["The book is ___ the table.",["on","at","to"],0],["We meet ___ Monday.",["in","on","at"],1],["I have lived here ___ 2020.",["since","for","during"],0]],
[["The room ___ every day.",["cleans","is cleaned","clean"],1],["The letter was ___.",["write","written","writing"],1],["English ___ worldwide.",["speaks","is spoken","speak"],1],["He said he ___ tired.",["was","is","be"],0],["The man ___ lives here is kind.",["who","where","when"],0]],
[["___ is your name?",["What","Where","When"],0],["___ do you live?",["What","Where","Who"],1],["She speaks English ___.",["good","well","bestly"],1],["I enjoy ___ books.",["read","reading","reads"],1],["What time ___ you wake up?",["do","does","are"],0]]
];

function enterSite(){
 document.getElementById("welcome").classList.add("hidden");
 document.getElementById("app").classList.remove("hidden");
 homePage();
 updateProgress();
 window.scrollTo(0,0);
}

// Brauzer xavfsizligi sababli sayt veb-sahifani o‘zi yopmaydi;
// CHIQISH kirish oynasiga qaytaradi.
function leaveSite(){
 document.getElementById("app").classList.add("hidden");
 document.getElementById("welcome").classList.remove("hidden");
 window.scrollTo(0,0);
}

const pageIds=["homePage","topicsPage","lessonPage","lessonQuizPage","testPage","resultsPage"];

function hidePages(){
 pageIds.forEach(id=>document.getElementById(id).classList.add("hidden"));
}

function homePage(){
 hidePages();
 document.getElementById("homePage").classList.remove("hidden");
 window.scrollTo(0,0);
}

function topicsPage(){
 hidePages();
 document.getElementById("topicsPage").classList.remove("hidden");
 renderTopics();
 window.scrollTo(0,0);
}

function testPage(){
 hidePages();
 document.getElementById("testPage").classList.remove("hidden");
 window.scrollTo(0,0);
}

function showLesson(){
 hidePages();
 document.getElementById("lessonPage").classList.remove("hidden");
}

function renderTopics(){
 let s=document.getElementById("search").value.toLowerCase();
 let arr=topics.filter(t=>(t.name+" "+t.group).toLowerCase().includes(s));
 document.getElementById("topicList").innerHTML=arr.map(t=>
 `<div class="section" onclick="openLesson(${t.id})">
 <div class="number">${t.group}</div>
 <b>${t.id+1}. ${t.name}</b>
 <p>${done.includes(t.id)?"✓ TUGATILGAN":"DARSNI OCHISH →"}</p>
 </div>`
 ).join("")||"<p class='muted'>Mavzu topilmadi.</p>";
}

function updateProgress(){
 document.getElementById("progressText").textContent=
 done.length+" / "+topics.length+" ta mavzu tugatilgan";
 document.getElementById("progressBar").style.width=
 (done.length/topics.length*100)+"%";
}

function openLesson(id){
 currentTopic=id;
 let t=topics[id],d=lessonData[t.groupId];

 hidePages();
 document.getElementById("lessonPage").classList.remove("hidden");

 document.getElementById("lessonLevel").textContent=t.group;
 document.getElementById("lessonTitle").textContent=(id+1)+". "+t.name;
 document.getElementById("lessonDescription").textContent=
 "Ushbu mavzuni qoida, formula va misollar orqali o‘rganing.";

 document.getElementById("lessonRule").textContent=d.rule;
 document.getElementById("lessonFormula").textContent=d.formula;

 document.getElementById("lessonExamples").innerHTML=
 d.examples.map(x=>`<div class="example">${x}</div>`).join("");

 document.getElementById("lessonTip").textContent=d.tip;
 window.scrollTo(0,0);
}

function lessonTest(){
 lessonAnswers={};
 currentLessonQuestions=lessonBanks[topics[currentTopic].groupId];

 document.getElementById("lessonQuizTitle").textContent=
 topics[currentTopic].name+" — TEST";

 document.getElementById("lessonResult").classList.add("hidden");

 document.getElementById("lessonQuestions").innerHTML=
 currentLessonQuestions.map((q,i)=>
 `<div class="card">
 <b>${i+1}. ${q[0]}</b>
 ${q[1].map((a,j)=>
 `<button class="option" id="l${i}_${j}"
 onclick="pickLesson(${i},${j})">${a}</button>`
 ).join("")}
 </div>`
 ).join("");

 hidePages();
 document.getElementById("lessonQuizPage").classList.remove("hidden");
 window.scrollTo(0,0);
}

function pickLesson(q,a){
 lessonAnswers[q]=a;
 currentLessonQuestions[q][1].forEach((_,j)=>
 document.getElementById("l"+q+"_"+j).classList.toggle("selected",j===a)
 );
}

function gradeLesson(){
 let score=0;

 currentLessonQuestions.forEach((q,i)=>{
  q[1].forEach((_,j)=>{
   let b=document.getElementById("l"+i+"_"+j);
   b.disabled=true;

   if(j===q[2])b.classList.add("correct");
   else if(lessonAnswers[i]===j)b.classList.add("wrong");
  });

  if(lessonAnswers[i]===q[2])score++;
 });

 let r=document.getElementById("lessonResult");
 r.classList.remove("hidden");

 r.innerHTML=`
 <h2>NATIJA: ${score}/5</h2>
 <p>${score>=4?"A’lo! Juda yaxshi!":"Yaxshi harakat! Yana mashq qiling."}</p>
 <button class="blue" onclick="lessonTest()">QAYTA ISHLASH</button>
 <button class="dark" onclick="topicsPage()">MAVZULAR</button>`;

 if(score>=3&&!done.includes(currentTopic)){
  done.push(currentTopic);
  localStorage.setItem("meg_done",JSON.stringify(done));
  updateProgress();
 }
}

function parseQuestions(raw){
 return raw.trim().split("\n").map(line=>{
  let p=line.split("|");
  return {q:p[0],a:p.slice(1,4),c:Number(p[4])};
 });
}

const easyRaw=`
I ___ a student.|am|is|are|0
She ___ my sister.|am|is|are|1
They ___ happy.|is|am|are|2
He ___ football every day.|play|plays|playing|1
I ___ English every day.|study|studies|studying|0
___ you like tea?|Do|Does|Are|0
She ___ TV now.|watch|watches|is watching|2
We ___ at school yesterday.|was|were|are|1
I ___ to the park yesterday.|go|went|gone|1
He didn't ___ football.|played|play|playing|1
There ___ a book on the table.|is|are|am|0
There ___ two pens.|is|are|am|1
I have ___ apple.|a|an|the|1
This is ___ book.|I|me|my|2
How ___ books do you have?|much|many|little|1
How ___ water do you need?|many|much|few|1
My birthday is ___ July.|at|on|in|2
I wake up ___ 7 o'clock.|at|on|in|0
She is taller ___ me.|then|than|that|1
He can ___.|swims|swimming|swim|2
I ___ swim when I was five.|can|could|must|1
We ___ visit tomorrow.|will|was|did|0
I am ___ now.|study|studying|studies|1
The plural of child is ___.|childs|children|childes|1
The opposite of hot is ___.|cold|warm|big|0
She ___ got a cat.|have|has|having|1
They ___ from Uzbekistan.|am|is|are|2
What ___ your name?|are|is|do|1
I like ___ football.|play|playing|plays|1
Thank you ___ much.|very|many|more|0`;

const mediumRaw=`
She ___ to school every day.|go|goes|going|1
I have ___ my homework.|finish|finished|finishing|1
They have lived here ___ 2020.|for|since|during|1
I have known him ___ five years.|since|for|at|1
If it rains, I ___ at home.|stay|will stay|would stay|1
If I were rich, I ___ a big house.|buy|will buy|would buy|2
You ___ see a doctor.|should|should to|shoulds|0
You ___ smoke here. It is forbidden.|don't have to|mustn't|could|1
The room ___ every day.|cleans|is cleaned|cleaning|1
The letter was ___ yesterday.|write|written|wrote|1
She said that she ___ tired.|is|was|be|1
He asked me where I ___.|live|lived|living|1
This is the man ___ helped me.|which|who|where|1
Ali is ___ than Vali.|tall|taller|tallest|1
This is the ___ film.|good|better|best|2
She speaks English ___.|good|well|betterly|1
I am interested ___ music.|on|at|in|2
He is good ___ mathematics.|at|on|in|0
I enjoy ___ books.|read|reading|to read|1
I want ___ English.|learn|learning|to learn|2
She has ___ arrived.|yet|just|ago|1
Have you ___ been to London?|ever|never|yet|0
I was watching TV when he ___.|comes|came|coming|1
They ___ playing at 5 yesterday.|was|were|are|1
You don't have to come means ___.|it is forbidden|it is not necessary|you must come|1
Neither Ali ___ Vali came.|or|nor|and|1
I wish I ___ more time.|have|had|having|1
Despite ___ tired, he worked.|be|being|was|1
The train leaves ___ 8.|in|on|at|2
She is used to ___ early.|get up|getting up|got up|1`;

const hardRaw=`
If I had studied, I ___ the exam.|would pass|would have passed|will pass|1
If she ___ earlier, she would be here now.|left|had left|leaves|1
I wish I ___ the answer.|know|knew|known|1
He ___ have forgotten the meeting.|must|should to|can to|0
You should ___ me earlier.|tell|have told|telling|1
The work ___ by tomorrow.|will finish|will be finished|finished|1
He is said ___ very intelligent.|be|to be|being|1
She asked me whether I ___ ready.|am|was|be|1
I regret ___ him the secret.|tell|to tell|telling|2
I stopped ___ some water.|drink|to drink|drinking|1
The more you practise, ___ you become.|the better|better|the best|0
No sooner had he arrived ___ it started raining.|when|than|then|1
Hardly had I sat down ___ the phone rang.|than|when|that|1
Not only ___ he clever, but he is also kind.|is|does|has|0
Were I you, I ___ accept the offer.|will|would|shall|1
She speaks as if she ___ everything.|knows|knew|known|1
The book, ___ I bought yesterday, is interesting.|who|which|where|1
Despite ___ late, he finished the work.|be|being|was|1
He denied ___ the money.|take|taking|to take|1
I would rather you ___ here.|stay|stayed|staying|1
The house needs ___.|paint|painting|to painting|1
By next year, I ___ here for ten years.|will work|will have worked|worked|1
The project ___ before we arrived.|had completed|had been completed|has complete|1
She suggested ___ earlier.|leave|to leave|leaving|2
He is accustomed to ___ hard.|work|working|worked|1
I would have called you if I ___ your number.|know|knew|had known|2
Little ___ he know about the problem.|do|did|does|1
It is high time we ___ home.|go|went|gone|1
The teacher insisted that he ___ on time.|is|be|was|1
Had I known the truth, I ___ differently.|would act|would have acted|will act|1`;

const testBanks={
 easy:parseQuestions(easyRaw),
 medium:parseQuestions(mediumRaw),
 hard:parseQuestions(hardRaw)
};

function startGeneral(level){
 generalLevel=level;
 generalAnswers={};
 generalQuestions=testBanks[level];

 document.getElementById("generalTitle").textContent=
 ({easy:"OSON DARAJA",medium:"O‘RTA DARAJA",hard:"QIYIN DARAJA"})[level]
 +" — ENGLISH TEST";

 document.getElementById("generalQuiz").classList.remove("hidden");
 document.getElementById("generalResult").classList.add("hidden");

 document.getElementById("generalQuestions").innerHTML=
 generalQuestions.map((q,i)=>
 `<div class="card">
 <b>${i+1}. ${q.q}</b>
 ${q.a.map((a,j)=>
 `<button class="option" id="g${i}_${j}"
 onclick="pickGeneral(${i},${j})">
 ${String.fromCharCode(65+j)}. ${a}
 </button>`
 ).join("")}
 </div>`
 ).join("");

 document.getElementById("questionCounter").textContent=
 "0 / 30 ta javob belgilandi";

 document.getElementById("quizProgress").style.width="0%";
 document.getElementById("generalQuiz").scrollIntoView({behavior:"smooth"});
}

function pickGeneral(q,a){
 generalAnswers[q]=a;

 generalQuestions[q].a.forEach((_,j)=>
 document.getElementById("g"+q+"_"+j).classList.toggle("selected",j===a)
 );

 let count=Object.keys(generalAnswers).length;

 document.getElementById("questionCounter").textContent=
 count+" / 30 ta javob belgilandi";

 document.getElementById("quizProgress").style.width=count/30*100+"%";
}

function finishGeneral(){
 let score=0;

 generalQuestions.forEach((q,i)=>{
  q.a.forEach((_,j)=>{
   let b=document.getElementById("g"+i+"_"+j);
   b.disabled=true;

   if(j===q.c)b.classList.add("correct");
   else if(generalAnswers[i]===j)b.classList.add("wrong");
  });

  if(generalAnswers[i]===q.c)score++;
 });

 let result=document.getElementById("generalResult");
 result.classList.remove("hidden");

 let percent=Math.round(score/30*100);

 result.innerHTML=`
 <h2>TEST NATIJASI 🏆</h2>
 <h1 style="color:#ff6578">${score}/30</h1>
 <h2>${percent}%</h2>
 <p>${percent>=90?"A’LO!":percent>=70?"JUDA YAXSHI!":percent>=50?"YAXSHI!":"KO‘PROQ MASHQ QILING!"}</p>
 <button class="blue" onclick="startGeneral(generalLevel)">QAYTA ISHLASH</button>
 <button class="dark" onclick="homePage()">BOSH SAHIFA</button>`;

 let saved=JSON.parse(localStorage.getItem("meg_results")||"[]");

 saved.unshift({
  level:generalLevel,
  score,
  date:new Date().toLocaleDateString("uz-UZ")
 });

 localStorage.setItem("meg_results",JSON.stringify(saved.slice(0,30)));
 result.scrollIntoView({behavior:"smooth"});
}

function resultsPage(){
 hidePages();
 document.getElementById("resultsPage").classList.remove("hidden");
 document.getElementById("doneCount").textContent=done.length;

 let saved=JSON.parse(localStorage.getItem("meg_results")||"[]");

 document.getElementById("savedResults").innerHTML=
 saved.length
 ?saved.map(r=>`
  <div class="example">
   <b>${r.level.toUpperCase()}</b>
   <p>Natija: ${r.score}/30</p>
   <small>${r.date}</small>
  </div>`).join("")
 :"Hozircha natijalar mavjud emas.";

 window.scrollTo(0,0);
}

// RASMLAR: telefonda accept=image/* fayl tanlagichi galereyani ochadi.
// IndexedDB katta rasmlarni localStorage limitisiz saqlash uchun ishlatiladi.
let imageDB=null,objectUrls=[];

const dbRequest=indexedDB.open("MyEnglishGroupImages",1);

dbRequest.onupgradeneeded=e=>{
 let db=e.target.result;
 if(!db.objectStoreNames.contains("photos"))
  db.createObjectStore("photos");
};

dbRequest.onsuccess=e=>{
 imageDB=e.target.result;
 restorePhotos();
};

dbRequest.onerror=()=>console.warn("Rasm saqlash ombori ochilmadi.");

function uploadPhoto(event,elementId,key){
 const file=event.target.files&&event.target.files[0];
 if(!file)return;

 if(!file.type.startsWith("image/")){
  alert("Iltimos, rasm faylini tanlang.");
  event.target.value="";
  return;
 }

 if(!imageDB){
  alert("Rasm ombori yuklanmoqda. Birozdan keyin qayta urinib ko‘ring.");
  return;
 }

 const tx=imageDB.transaction("photos","readwrite");
 tx.objectStore("photos").put(file,key);

 tx.oncomplete=()=>{
  const url=URL.createObjectURL(file);
  objectUrls.push(url);
  document.getElementById(elementId).src=url;
  alert("Rasm saqlandi!");
  event.target.value="";
 };

 tx.onerror=()=>alert("Rasmni saqlab bo‘lmadi. Telefon xotirasini tekshiring.");
}

function restorePhotos(){
 if(!imageDB)return;

 [["welcome","welcomeImage"],["photo1","photo1"],["photo2","photo2"],["photo3","photo3"]]
 .forEach(([key,id])=>{
  const req=imageDB.transaction("photos","readonly").objectStore("photos").get(key);

  req.onsuccess=()=>{
   if(req.result){
    const url=URL.createObjectURL(req.result);
    objectUrls.push(url);
    document.getElementById(id).src=url;
   }
  };
 });
}
</script>
</body>
</html>
