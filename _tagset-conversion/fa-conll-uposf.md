---
layout: base
title: 'Tagset fa::conll conversion to universal POS tags and features'
---

<a href="index.html">all tables</a>

## Tagset fa::conll

**Disclaimer:**
This conversion table was generated automatically via Interset.
It uses only tags (+ features) as input, therefore it is only an approximation.
Some tags can only be mapped if we also know the lemma or the syntactic context; such information has not been available here.
The table requires manual postprocessing in order to provide accurate and complete information.

Tagset <tt>fa::conll</tt>, total 271 tags.

<table>
  <tr style="background:lightgray"><td>ADJ AJCM attachment=ISO</td><td>=&gt;</td><td>ADJ</td><td>Degree=Comp</td><td><em>بیشتر, بیش, بهتر, بیشتری, کمتر</em></td></tr>
  <tr><td>ADJ AJCM attachment=NXT</td><td>=&gt;</td><td>ADJ</td><td>Degree=Comp</td><td><em>نزدیک‌تر, پیش‌تر, بالغ‌تر, عاقل‌تر, تاریخی‌تر</em></td></tr>
  <tr style="background:lightgray"><td>ADJ AJP attachment=ISO</td><td>=&gt;</td><td>ADJ</td><td>Degree=Pos</td><td><em>دیگر, اسلامی, بزرگ, جدید, مختلف</em></td></tr>
  <tr><td>ADJ AJP attachment=ISO|number=SING</td><td>=&gt;</td><td>ADJ</td><td>Degree=Pos|Number=Sing</td><td><em>صاحب</em></td></tr>
  <tr style="background:lightgray"><td>ADJ AJP attachment=NXT</td><td>=&gt;</td><td>ADJ</td><td>Degree=Pos</td><td><em>امیدوار, معتقد, مجبور, متأسف, تنها</em></td></tr>
  <tr><td>ADJ AJP attachment=PRV</td><td>=&gt;</td><td>ADJ</td><td>Degree=Pos</td><td><em>معتقد, خواستار, زیبا</em></td></tr>
  <tr style="background:lightgray"><td>ADJ AJSUP attachment=ISO</td><td>=&gt;</td><td>ADJ</td><td>Degree=Sup</td><td><em>بهترین, مهم‌ترین, بزرگ‌ترین, بیشترین, قوی‌ترین</em></td></tr>
  <tr><td>ADR POSADR attachment=ISO</td><td>=&gt;</td><td>INTJ</td><td>Case=Voc</td><td><em>ا</em></td></tr>
  <tr style="background:lightgray"><td>ADR POSADR attachment=PRV</td><td>=&gt;</td><td>INTJ</td><td>Case=Voc</td><td><em>ا</em></td></tr>
  <tr><td>ADR PRADR attachment=ISO</td><td>=&gt;</td><td>INTJ</td><td>Case=Voc</td><td><em>ای, یا, آهای</em></td></tr>
  <tr style="background:lightgray"><td>ADV AVCM attachment=ISO</td><td>=&gt;</td><td>ADV</td><td>Degree=Comp</td><td><em>بیشتر, بیش, کمتر, بهتر, زودتر</em></td></tr>
  <tr><td>ADV AVP attachment=ISO</td><td>=&gt;</td><td>ADV</td><td>Degree=Pos</td><td><em>هم, تنها, دیگر, خوب, پس</em></td></tr>
  <tr style="background:lightgray"><td>ADV AVP attachment=NXT</td><td>=&gt;</td><td>ADV</td><td>Degree=Pos</td><td><em>کجا, بیرون</em></td></tr>
  <tr><td>ADV AVSUP attachment=ISO</td><td>=&gt;</td><td>ADV</td><td>Degree=Sup</td><td><em>دوباره</em></td></tr>
  <tr style="background:lightgray"><td>ADV SADV attachment=ISO</td><td>=&gt;</td><td>ADV</td><td>_</td><td><em>هم, نیز, حتی, نه, خیلی</em></td></tr>
  <tr><td>ADV SADV attachment=NXT</td><td>=&gt;</td><td>ADV</td><td>_</td><td><em>کجا</em></td></tr>
  <tr style="background:lightgray"><td>ADV SADV attachment=PRV</td><td>=&gt;</td><td>ADV</td><td>_</td><td><em>م, کجا</em></td></tr>
  <tr><td>CONJ CONJ attachment=ISO</td><td>=&gt;</td><td>CONJ</td><td>_</td><td><em>و, یا, اما, ولی, که</em></td></tr>
  <tr style="background:lightgray"><td>IDEN IDEN attachment=ISO</td><td>=&gt;</td><td>NOUN</td><td>_</td><td><em>ملا</em></td></tr>
  <tr><td>IDEN IDEN attachment=ISO|number=SING</td><td>=&gt;</td><td>NOUN</td><td>Number=Sing</td><td><em>امام, دکتر, شهید, سید, آیت‌الله</em></td></tr>
  <tr style="background:lightgray"><td>N ANM attachment=ISO</td><td>=&gt;</td><td>NOUN</td><td>Animacy=Anim</td><td><em>اجارۀ, آقای, روبیگو, پس , سرلوحۀ</em></td></tr>
  <tr><td>N ANM attachment=ISO|number=PLUR</td><td>=&gt;</td><td>NOUN</td><td>Animacy=Anim|Number=Plur</td><td><em>مردم, کسانی, دیگران, افراد, زنان</em></td></tr>
  <tr style="background:lightgray"><td>N ANM attachment=ISO|number=SING</td><td>=&gt;</td><td>NOUN</td><td>Animacy=Anim|Number=Sing</td><td><em>خدا, کسی, انسان, خداوند, نفر</em></td></tr>
  <tr><td>N ANM attachment=NXT|number=PLUR</td><td>=&gt;</td><td>NOUN</td><td>Animacy=Anim|Number=Plur</td><td><em>انسان‌ها, زن‌ها, فرشته‌ها, طالبان, دیگران</em></td></tr>
  <tr style="background:lightgray"><td>N ANM attachment=NXT|number=SING</td><td>=&gt;</td><td>NOUN</td><td>Animacy=Anim|Number=Sing</td><td><em>خدا, خدای, خداوند, پروردگار, الرضا</em></td></tr>
  <tr><td>N IANM attachment=ISO</td><td>=&gt;</td><td>NOUN</td><td>Animacy=Inan</td><td><em>اسلام, هزار, ایجاد, وقتی, تمام</em></td></tr>
  <tr style="background:lightgray"><td>N IANM attachment=ISO|number=PLUR</td><td>=&gt;</td><td>NOUN</td><td>Animacy=Inan|Number=Plur</td><td><em>همۀ, همه, حقوق, آثار, شرایط</em></td></tr>
  <tr><td>N IANM attachment=ISO|number=SING</td><td>=&gt;</td><td>NOUN</td><td>Animacy=Inan|Number=Sing</td><td><em>سال, کار, ایران, روز, دست</em></td></tr>
  <tr style="background:lightgray"><td>N IANM attachment=NXT|number=PLUR</td><td>=&gt;</td><td>NOUN</td><td>Animacy=Inan|Number=Plur</td><td><em>سال‌ها, روزها, ضرورت‌هایی‌, فروافتادن‌ها, مدت‌ها</em></td></tr>
  <tr><td>N IANM attachment=NXT|number=SING</td><td>=&gt;</td><td>NOUN</td><td>Animacy=Inan|Number=Sing</td><td><em>اینجا, دوست, کجا, نگاه, عمری</em></td></tr>
  <tr style="background:lightgray"><td>N IANM attachment=PRV|number=SING</td><td>=&gt;</td><td>NOUN</td><td>Animacy=Inan|Number=Sing</td><td><em>پرداخت, جا</em></td></tr>
  <tr><td>PART PART attachment=ISO</td><td>=&gt;</td><td>PART</td><td>_</td><td><em>آیا, که, مگر, را, دیگر</em></td></tr>
  <tr style="background:lightgray"><td>PART PART attachment=PRV</td><td>=&gt;</td><td>PART</td><td>_</td><td><em>را</em></td></tr>
  <tr><td>POSNUM POSNUM attachment=ISO</td><td>=&gt;</td><td>NUM</td><td>_</td><td><em>اول, دوم, سوم, چهارم, نخست</em></td></tr>
  <tr style="background:lightgray"><td>POSTP POSTP attachment=ISO</td><td>=&gt;</td><td>ADP</td><td>AdpType=Post</td><td><em>را, چون, از, رفتۀ, مرا</em></td></tr>
  <tr><td>POSTP POSTP attachment=NXT</td><td>=&gt;</td><td>ADP</td><td>AdpType=Post</td><td><em>را</em></td></tr>
  <tr style="background:lightgray"><td>POSTP POSTP attachment=PRV</td><td>=&gt;</td><td>ADP</td><td>AdpType=Post</td><td><em>را</em></td></tr>
  <tr><td>PR CREFX attachment=ISO</td><td>=&gt;</td><td>PRON</td><td>PronType=Prs|Reflex=Yes</td><td><em>خود, خویش, هم, یکدیگر, همدیگر</em></td></tr>
  <tr style="background:lightgray"><td>PR CREFX attachment=ISO|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|PronType=Prs|Reflex=Yes</td><td><em>خود, هم, کجا</em></td></tr>
  <tr><td>PR CREFX person=1|attachment=ISO|number=PLUR</td><td>=&gt;</td><td>PRON</td><td>Number=Plur|Person=1|PronType=Prs|Reflex=Yes</td><td><em></em></td></tr>
  <tr style="background:lightgray"><td>PR CREFX person=1|attachment=ISO|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|Person=1|PronType=Prs|Reflex=Yes</td><td><em>خود, هم, دفتر, یکدیگر, من</em></td></tr>
  <tr><td>PR CREFX person=1|attachment=PRV|number=PLUR</td><td>=&gt;</td><td>PRON</td><td>Number=Plur|Person=1|PronType=Prs|Reflex=Yes</td><td><em>مان</em></td></tr>
  <tr style="background:lightgray"><td>PR CREFX person=1|attachment=PRV|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|Person=1|PronType=Prs|Reflex=Yes</td><td><em>م, مان</em></td></tr>
  <tr><td>PR CREFX person=2|attachment=ISO|number=PLUR</td><td>=&gt;</td><td>PRON</td><td>Number=Plur|Person=2|PronType=Prs|Reflex=Yes</td><td><em>خودتان</em></td></tr>
  <tr style="background:lightgray"><td>PR CREFX person=2|attachment=ISO|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|Person=2|PronType=Prs|Reflex=Yes</td><td><em>تو</em></td></tr>
  <tr><td>PR CREFX person=3|attachment=ISO|number=PLUR</td><td>=&gt;</td><td>PRON</td><td>Number=Plur|Person=3|PronType=Prs|Reflex=Yes</td><td><em>هم, همدیگر, خودشان, خود, یکدیگر</em></td></tr>
  <tr style="background:lightgray"><td>PR CREFX person=3|attachment=ISO|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|Person=3|PronType=Prs|Reflex=Yes</td><td><em>خود, خویش, هم, یکدیگر, همدیگر</em></td></tr>
  <tr><td>PR DEMON attachment=ISO</td><td>=&gt;</td><td>PRON</td><td>PronType=Dem</td><td><em>آن, این, چنین, چنان, همچنان</em></td></tr>
  <tr style="background:lightgray"><td>PR DEMON attachment=ISO|number=PLUR</td><td>=&gt;</td><td>PRON</td><td>Number=Plur|PronType=Dem</td><td><em>آنها, اینها, آن‌ها, آنان, همانها</em></td></tr>
  <tr><td>PR DEMON attachment=ISO|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|PronType=Dem</td><td><em>آن, این, همین, چنان, آنجا</em></td></tr>
  <tr style="background:lightgray"><td>PR DEMON attachment=NXT|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|PronType=Dem</td><td><em>این, آن, همان</em></td></tr>
  <tr><td>PR DEMON attachment=PRV|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|PronType=Dem</td><td><em>ان</em></td></tr>
  <tr style="background:lightgray"><td>PR DEMON person=1|attachment=ISO|number=PLUR</td><td>=&gt;</td><td>PRON</td><td>Number=Plur|Person=1|PronType=Dem</td><td><em></em></td></tr>
  <tr><td>PR DEMON person=1|attachment=ISO|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|Person=1|PronType=Dem</td><td><em>این, چنین</em></td></tr>
  <tr style="background:lightgray"><td>PR DEMON person=1|attachment=NXT|number=PLUR</td><td>=&gt;</td><td>PRON</td><td>Number=Plur|Person=1|PronType=Dem</td><td><em>ما</em></td></tr>
  <tr><td>PR DEMON person=3|attachment=ISO</td><td>=&gt;</td><td>PRON</td><td>Person=3|PronType=Dem</td><td><em>آن</em></td></tr>
  <tr style="background:lightgray"><td>PR DEMON person=3|attachment=ISO|number=PLUR</td><td>=&gt;</td><td>PRON</td><td>Number=Plur|Person=3|PronType=Dem</td><td><em>آنان, آنها, اینها, آن</em></td></tr>
  <tr><td>PR DEMON person=3|attachment=ISO|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|Person=3|PronType=Dem</td><td><em>آن, این, چنان, چنین, همین</em></td></tr>
  <tr style="background:lightgray"><td>PR DEMON person=3|attachment=NXT|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|Person=3|PronType=Dem</td><td><em>او</em></td></tr>
  <tr><td>PR INTG attachment=ISO</td><td>=&gt;</td><td>PRON</td><td>PronType=Int</td><td><em>چه, کجا, چگونه, چی, چرا</em></td></tr>
  <tr style="background:lightgray"><td>PR INTG attachment=ISO|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|PronType=Int</td><td><em>چه, که</em></td></tr>
  <tr><td>PR INTG attachment=NXT</td><td>=&gt;</td><td>PRON</td><td>PronType=Int</td><td><em>چی, کجا, کی</em></td></tr>
  <tr style="background:lightgray"><td>PR INTG attachment=NXT|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|PronType=Int</td><td><em>چی, کی</em></td></tr>
  <tr><td>PR INTG person=1|attachment=ISO|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|Person=1|PronType=Int</td><td><em>چه</em></td></tr>
  <tr style="background:lightgray"><td>PR INTG person=3|attachment=ISO|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|Person=3|PronType=Int</td><td><em>چه, چی, کجا, کی, کدام</em></td></tr>
  <tr><td>PR JOPER person=1|attachment=ISO|number=PLUR</td><td>=&gt;</td><td>PRON</td><td>Number=Plur|Person=1|PronType=Prs|Variant=Short</td><td><em></em></td></tr>
  <tr style="background:lightgray"><td>PR JOPER person=1|attachment=ISO|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|Person=1|PronType=Prs|Variant=Short</td><td><em>م</em></td></tr>
  <tr><td>PR JOPER person=1|attachment=NXT|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|Person=1|PronType=Prs|Variant=Short</td><td><em>م</em></td></tr>
  <tr style="background:lightgray"><td>PR JOPER person=1|attachment=PRV|number=PLUR</td><td>=&gt;</td><td>PRON</td><td>Number=Plur|Person=1|PronType=Prs|Variant=Short</td><td><em>مان</em></td></tr>
  <tr><td>PR JOPER person=1|attachment=PRV|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|Person=1|PronType=Prs|Variant=Short</td><td><em>م, ام, یم</em></td></tr>
  <tr style="background:lightgray"><td>PR JOPER person=2|attachment=ISO|number=PLUR</td><td>=&gt;</td><td>PRON</td><td>Number=Plur|Person=2|PronType=Prs|Variant=Short</td><td><em></em></td></tr>
  <tr><td>PR JOPER person=2|attachment=ISO|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|Person=2|PronType=Prs|Variant=Short</td><td><em></em></td></tr>
  <tr style="background:lightgray"><td>PR JOPER person=2|attachment=PRV|number=PLUR</td><td>=&gt;</td><td>PRON</td><td>Number=Plur|Person=2|PronType=Prs|Variant=Short</td><td><em>تان</em></td></tr>
  <tr><td>PR JOPER person=2|attachment=PRV|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|Person=2|PronType=Prs|Variant=Short</td><td><em>ت, یت</em></td></tr>
  <tr style="background:lightgray"><td>PR JOPER person=3|attachment=ISO|number=PLUR</td><td>=&gt;</td><td>PRON</td><td>Number=Plur|Person=3|PronType=Prs|Variant=Short</td><td><em>آنها, شان</em></td></tr>
  <tr><td>PR JOPER person=3|attachment=ISO|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|Person=3|PronType=Prs|Variant=Short</td><td><em>ش</em></td></tr>
  <tr style="background:lightgray"><td>PR JOPER person=3|attachment=NXT|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|Person=3|PronType=Prs|Variant=Short</td><td><em>یش</em></td></tr>
  <tr><td>PR JOPER person=3|attachment=PRV|number=PLUR</td><td>=&gt;</td><td>PRON</td><td>Number=Plur|Person=3|PronType=Prs|Variant=Short</td><td><em>شان</em></td></tr>
  <tr style="background:lightgray"><td>PR JOPER person=3|attachment=PRV|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|Person=3|PronType=Prs|Variant=Short</td><td><em>ش, اش, یش, شان</em></td></tr>
  <tr><td>PR SEPER attachment=ISO</td><td>=&gt;</td><td>PRON</td><td>PronType=Prs</td><td><em>هم, آن, یکدیگر, آنها, همه</em></td></tr>
  <tr style="background:lightgray"><td>PR SEPER attachment=ISO|number=PLUR</td><td>=&gt;</td><td>PRON</td><td>Number=Plur|PronType=Prs</td><td><em>آنها, همه, اینها</em></td></tr>
  <tr><td>PR SEPER attachment=ISO|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|PronType=Prs</td><td><em>آن, این, چی</em></td></tr>
  <tr style="background:lightgray"><td>PR SEPER person=1|attachment=ISO|number=PLUR</td><td>=&gt;</td><td>PRON</td><td>Number=Plur|Person=1|PronType=Prs</td><td><em>ما, خودمان, خود, همه, همۀ</em></td></tr>
  <tr><td>PR SEPER person=1|attachment=ISO|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|Person=1|PronType=Prs</td><td><em>من, خودم, آن, بنده, این</em></td></tr>
  <tr style="background:lightgray"><td>PR SEPER person=1|attachment=NXT|number=PLUR</td><td>=&gt;</td><td>PRON</td><td>Number=Plur|Person=1|PronType=Prs</td><td><em>ما</em></td></tr>
  <tr><td>PR SEPER person=1|attachment=NXT|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|Person=1|PronType=Prs</td><td><em>م, من</em></td></tr>
  <tr style="background:lightgray"><td>PR SEPER person=1|attachment=PRV|number=PLUR</td><td>=&gt;</td><td>PRON</td><td>Number=Plur|Person=1|PronType=Prs</td><td><em>مان</em></td></tr>
  <tr><td>PR SEPER person=1|attachment=PRV|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|Person=1|PronType=Prs</td><td><em>م</em></td></tr>
  <tr style="background:lightgray"><td>PR SEPER person=2|attachment=ISO|number=PLUR</td><td>=&gt;</td><td>PRON</td><td>Number=Plur|Person=2|PronType=Prs</td><td><em>شما, خودتان, شماها, خودشان, خودمان</em></td></tr>
  <tr><td>PR SEPER person=2|attachment=ISO|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|Person=2|PronType=Prs</td><td><em>تو, خودت, شما</em></td></tr>
  <tr style="background:lightgray"><td>PR SEPER person=2|attachment=NXT|number=PLUR</td><td>=&gt;</td><td>PRON</td><td>Number=Plur|Person=2|PronType=Prs</td><td><em>شما</em></td></tr>
  <tr><td>PR SEPER person=2|attachment=NXT|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|Person=2|PronType=Prs</td><td><em>تو, توی</em></td></tr>
  <tr style="background:lightgray"><td>PR SEPER person=3|attachment=ISO|number=PLUR</td><td>=&gt;</td><td>PRON</td><td>Number=Plur|Person=3|PronType=Prs</td><td><em>آنها, آنان, ایشان, همه, خودشان</em></td></tr>
  <tr><td>PR SEPER person=3|attachment=ISO|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|Person=3|PronType=Prs</td><td><em>او, آن, این, وی, خودش</em></td></tr>
  <tr style="background:lightgray"><td>PR SEPER person=3|attachment=NXT|number=PLUR</td><td>=&gt;</td><td>PRON</td><td>Number=Plur|Person=3|PronType=Prs</td><td><em>آنها, آنان</em></td></tr>
  <tr><td>PR SEPER person=3|attachment=NXT|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|Person=3|PronType=Prs</td><td><em>م, او, چی, این, کجا</em></td></tr>
  <tr style="background:lightgray"><td>PR SEPER person=3|attachment=PRV|number=SING</td><td>=&gt;</td><td>PRON</td><td>Number=Sing|Person=3|PronType=Prs</td><td><em>را, ش, ین, ان, و</em></td></tr>
  <tr><td>PREM AMBAJ attachment=ISO</td><td>=&gt;</td><td>DET</td><td>PronType=Ind,Neg,Tot</td><td><em>هر, چند, هیچ, برخی, همه</em></td></tr>
  <tr style="background:lightgray"><td>PREM DEMAJ attachment=ISO</td><td>=&gt;</td><td>DET</td><td>PronType=Dem</td><td><em>این, آن, همان, همین, چنین</em></td></tr>
  <tr><td>PREM DEMAJ attachment=PRV</td><td>=&gt;</td><td>DET</td><td>PronType=Dem</td><td><em>ین, دین, ان</em></td></tr>
  <tr style="background:lightgray"><td>PREM EXAJ attachment=ISO</td><td>=&gt;</td><td>DET</td><td>PronType=Exc</td><td><em>چه, چقدر, آن, چند, عجب</em></td></tr>
  <tr><td>PREM QUAJ attachment=ISO</td><td>=&gt;</td><td>DET</td><td>PronType=Int</td><td><em>چه, کدام, چند, کدامین, چه‌</em></td></tr>
  <tr style="background:lightgray"><td>PRENUM PRENUM attachment=ISO</td><td>=&gt;</td><td>NUM</td><td>_</td><td><em>یک, دو, سه, اولین, چهار</em></td></tr>
  <tr><td>PREP PREP attachment=ISO</td><td>=&gt;</td><td>ADP</td><td>AdpType=Prep</td><td><em>به, در, از, با, برای</em></td></tr>
  <tr style="background:lightgray"><td>PREP PREP attachment=NXT</td><td>=&gt;</td><td>ADP</td><td>AdpType=Prep</td><td><em>بد, برای, نزد, از, ب</em></td></tr>
  <tr><td>PREP PREP attachment=PRV</td><td>=&gt;</td><td>ADP</td><td>AdpType=Prep</td><td><em>را</em></td></tr>
  <tr style="background:lightgray"><td>PSUS PSUS attachment=ISO</td><td>=&gt;</td><td>PART</td><td>PartType=Mod</td><td><em>کاش, نه, انگار, یعنی, بله</em></td></tr>
  <tr><td>PSUS PSUS attachment=NXT</td><td>=&gt;</td><td>PART</td><td>PartType=Mod</td><td><em>خدای</em></td></tr>
  <tr style="background:lightgray"><td>PUNC PUNC attachment=ISO</td><td>=&gt;</td><td>PUNCT</td><td>_</td><td><em>., ،, ؟, «, »</em></td></tr>
  <tr><td>PUNC PUNC attachment=PRV</td><td>=&gt;</td><td>PUNCT</td><td>_</td><td><em>ند, .</em></td></tr>
  <tr style="background:lightgray"><td>SUBR SUBR attachment=ISO</td><td>=&gt;</td><td>SCONJ</td><td>_</td><td><em>که, اگر, تا, زیرا, چون</em></td></tr>
  <tr><td>SUBR SUBR attachment=PRV</td><td>=&gt;</td><td>SCONJ</td><td>_</td><td><em>که</em></td></tr>
  <tr style="background:lightgray"><td>V ACT attachment=ISO|number=PLUR|tma=AY</td><td>=&gt;</td><td>VERB</td><td>Mood=Ind|Number=Plur|Tense=Fut|VerbForm=Fin|Voice=Act</td><td><em>خواهند کرد</em></td></tr>
  <tr><td>V ACT attachment=ISO|number=PLUR|tma=GN</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Plur|Tense=Nar|VerbForm=Fin|Voice=Act</td><td><em>تاخته‌ایم, کرده‌اند, گرفته‌اند</em></td></tr>
  <tr style="background:lightgray"><td>V ACT attachment=ISO|number=PLUR|tma=GS</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Plur|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>کردند</em></td></tr>
  <tr><td>V ACT attachment=ISO|number=PLUR|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Plur|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>می‌کاریم</em></td></tr>
  <tr style="background:lightgray"><td>V ACT attachment=ISO|number=PLUR|tma=HEL</td><td>=&gt;</td><td>VERB</td><td>Mood=Sub|Number=Plur|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>کنیم, نفهمند</em></td></tr>
  <tr><td>V ACT attachment=ISO|number=SING|tma=GB</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Sing|Tense=Pqp|VerbForm=Fin|Voice=Act</td><td><em>خواسته بود</em></td></tr>
  <tr style="background:lightgray"><td>V ACT attachment=ISO|number=SING|tma=GEL</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Sub|Number=Sing|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>گردانیده باشد</em></td></tr>
  <tr><td>V ACT attachment=ISO|number=SING|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>است, می‌کند, نمی‌تواند</em></td></tr>
  <tr style="background:lightgray"><td>V ACT attachment=ISO|number=SING|tma=HEL</td><td>=&gt;</td><td>VERB</td><td>Mood=Sub|Number=Sing|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>بزنم, بدانی, کنم</em></td></tr>
  <tr><td>V ACT attachment=ISO|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>نمی‌توان, می‌توان</em></td></tr>
  <tr style="background:lightgray"><td>V ACT attachment=ISO|tma=HEL</td><td>=&gt;</td><td>VERB</td><td>Mood=Sub|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>نباید, می‌بایست, باید</em></td></tr>
  <tr><td>V ACT person=1|attachment=ISO|number=PLUR|tma=AY</td><td>=&gt;</td><td>VERB</td><td>Mood=Ind|Number=Plur|Person=1|Tense=Fut|VerbForm=Fin|Voice=Act</td><td><em>خواهیم کرد, نخواهیم کرد, خواهیم داد, خواهیم بود, خواهیم توانست</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=1|attachment=ISO|number=PLUR|tma=GB</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Plur|Person=1|Tense=Pqp|VerbForm=Fin|Voice=Act</td><td><em>کرده بودیم, داده بودیم, زده بودیم, آمده بودیم, کشیده بودیم</em></td></tr>
  <tr><td>V ACT person=1|attachment=ISO|number=PLUR|tma=GEL</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Sub|Number=Plur|Person=1|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>کرده باشیم, داشته باشیم, داده باشیم, کشیده باشیم, زده باشیم</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=1|attachment=ISO|number=PLUR|tma=GES</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Plur|Person=1|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>می‌کردیم, می‌دادیم, می‌زدیم, می‌رفتیم, می‌خندیدیم</em></td></tr>
  <tr><td>V ACT person=1|attachment=ISO|number=PLUR|tma=GN</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Plur|Person=1|Tense=Nar|VerbForm=Fin|Voice=Act</td><td><em>کرده‌ایم, داده‌ایم, داشته‌ایم, گرفته‌ایم, آورده‌ایم</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=1|attachment=ISO|number=PLUR|tma=GS</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Plur|Person=1|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>کردیم, دادیم, داشتیم, بودیم, رفتیم</em></td></tr>
  <tr><td>V ACT person=1|attachment=ISO|number=PLUR|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Plur|Person=1|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>می‌کنیم, هستیم, داریم, می‌دهیم, می‌گیریم</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=1|attachment=ISO|number=PLUR|tma=HEL</td><td>=&gt;</td><td>VERB</td><td>Mood=Sub|Number=Plur|Person=1|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>کنیم, بکنیم, بتوانیم, بدهیم, بزنیم</em></td></tr>
  <tr><td>V ACT person=1|attachment=ISO|number=SING|tma=AY</td><td>=&gt;</td><td>VERB</td><td>Mood=Ind|Number=Sing|Person=1|Tense=Fut|VerbForm=Fin|Voice=Act</td><td><em>خواهم کرد, خواهم داد, خواهم داشت, نخواهم کرد, خواهم کشید</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=1|attachment=ISO|number=SING|tma=GB</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Sing|Person=1|Tense=Pqp|VerbForm=Fin|Voice=Act</td><td><em>کرده بودم, داده بودم, گرفته بودم, گذاشته بودم, زده بودم</em></td></tr>
  <tr><td>V ACT person=1|attachment=ISO|number=SING|tma=GBESE</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Sub|Number=Sing|Person=1|Tense=Pqp|VerbForm=Fin|Voice=Act</td><td><em>بده</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=1|attachment=ISO|number=SING|tma=GEL</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Sub|Number=Sing|Person=1|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>کرده باشم, داشته باشم, داده باشم, زده باشم, برخورده باشم</em></td></tr>
  <tr><td>V ACT person=1|attachment=ISO|number=SING|tma=GES</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=1|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>می‌کردم, می‌زدم, می‌خواستم, می‌دادم, می‌دانستم</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=1|attachment=ISO|number=SING|tma=GESEL</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Sub|Number=Sing|Person=1|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>برمی‌گردانیدم</em></td></tr>
  <tr><td>V ACT person=1|attachment=ISO|number=SING|tma=GN</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Sing|Person=1|Tense=Nar|VerbForm=Fin|Voice=Act</td><td><em>کرده‌ام, داده‌ام, داشته‌ام, زده‌ام, گرفته‌ام</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=1|attachment=ISO|number=SING|tma=GNES</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=1|Tense=Nar|VerbForm=Fin|Voice=Act</td><td><em>می‌کرده‌ام</em></td></tr>
  <tr><td>V ACT person=1|attachment=ISO|number=SING|tma=GS</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Sing|Person=1|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>کردم, گفتم, بودم, داشتم, دیدم</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=1|attachment=ISO|number=SING|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>می‌کنم, دارم, می‌خواهم, هستم, می‌دهم</em></td></tr>
  <tr><td>V ACT person=1|attachment=ISO|number=SING|tma=HA</td><td>=&gt;</td><td>VERB</td><td>Mood=Imp|Number=Sing|Person=1|VerbForm=Fin|Voice=Act</td><td><em>بروم, نکن</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=1|attachment=ISO|number=SING|tma=HEL</td><td>=&gt;</td><td>VERB</td><td>Mood=Sub|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>کنم, بروم, بدهم, بزنم, بکنم</em></td></tr>
  <tr><td>V ACT person=1|attachment=NXT|number=PLUR|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Plur|Person=1|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>می‌شناسیم</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=1|attachment=NXT|number=SING|tma=GS</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Sing|Person=1|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>دیدم</em></td></tr>
  <tr><td>V ACT person=1|attachment=NXT|number=SING|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>م, نمی‌یابم, بازمی‌جویم, می‌جویم</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=1|attachment=PRV|number=PLUR|tma=AY</td><td>=&gt;</td><td>VERB</td><td>Mood=Ind|Number=Plur|Person=1|Tense=Fut|VerbForm=Fin|Voice=Act</td><td><em>یم</em></td></tr>
  <tr><td>V ACT person=1|attachment=PRV|number=PLUR|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Plur|Person=1|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>یم, ایم</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=1|attachment=PRV|number=SING|tma=AY</td><td>=&gt;</td><td>VERB</td><td>Mood=Ind|Number=Sing|Person=1|Tense=Fut|VerbForm=Fin|Voice=Act</td><td><em>ستم</em></td></tr>
  <tr><td>V ACT person=1|attachment=PRV|number=SING|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>م, ام, یم, ییم</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=1|attachment=PRV|number=SING|tma=HEL</td><td>=&gt;</td><td>VERB</td><td>Mood=Sub|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>کنم</em></td></tr>
  <tr><td>V ACT person=2|attachment=ISO|number=PLUR</td><td>=&gt;</td><td>VERB</td><td>Number=Plur|Person=2|Voice=Act</td><td><em>ورزید</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=2|attachment=ISO|number=PLUR|tma=AY</td><td>=&gt;</td><td>VERB</td><td>Mood=Ind|Number=Plur|Person=2|Tense=Fut|VerbForm=Fin|Voice=Act</td><td><em>خواهید کرد, خواهید زد, خواهید دید, خواهید بود, خواهید شد</em></td></tr>
  <tr><td>V ACT person=2|attachment=ISO|number=PLUR|tma=GB</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Plur|Person=2|Tense=Pqp|VerbForm=Fin|Voice=Act</td><td><em>کرده بودید, داشته بودید, نکوهیده بودید, برخاسته بودید, نکرده بودید</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=2|attachment=ISO|number=PLUR|tma=GEL</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Sub|Number=Plur|Person=2|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>کرده باشید, داشته باشید, داده باشید, کرده باشیم, خورده باشید</em></td></tr>
  <tr><td>V ACT person=2|attachment=ISO|number=PLUR|tma=GES</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Plur|Person=2|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>می‌کردید, نمی‌گذاشتید, می‌آموختید, می‌پرداختید, می‌پرستیدید</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=2|attachment=ISO|number=PLUR|tma=GN</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Plur|Person=2|Tense=Nar|VerbForm=Fin|Voice=Act</td><td><em>کرده‌اید, داده‌اید, زده‌اید, آورده‌اید, کشیده‌اید</em></td></tr>
  <tr><td>V ACT person=2|attachment=ISO|number=PLUR|tma=GNES</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Plur|Person=2|Tense=Nar|VerbForm=Fin|Voice=Act</td><td><em>می‌کرده‌اید, می‌شناخته‌اید</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=2|attachment=ISO|number=PLUR|tma=GS</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Plur|Person=2|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>کردید, بودید, دادید, زدید, نوشتید</em></td></tr>
  <tr><td>V ACT person=2|attachment=ISO|number=PLUR|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Plur|Person=2|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>می‌کنید, دارید, می‌توانید, هستید, می‌خواهید</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=2|attachment=ISO|number=PLUR|tma=HA</td><td>=&gt;</td><td>VERB</td><td>Mood=Imp|Number=Plur|Person=2|VerbForm=Fin|Voice=Act</td><td><em>کنید, نکنید, دهید, بدهید, باشید</em></td></tr>
  <tr><td>V ACT person=2|attachment=ISO|number=PLUR|tma=HEL</td><td>=&gt;</td><td>VERB</td><td>Mood=Sub|Number=Plur|Person=2|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>کنید, باشید, بدهید, نکنید, بکنید</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=2|attachment=ISO|number=SING|tma=AY</td><td>=&gt;</td><td>VERB</td><td>Mood=Ind|Number=Sing|Person=2|Tense=Fut|VerbForm=Fin|Voice=Act</td><td><em>خواهی کرد, خواهی داد, خواهی سوزاند, فروخواهد ماند, خواهی افشاند</em></td></tr>
  <tr><td>V ACT person=2|attachment=ISO|number=SING|tma=GB</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Sing|Person=2|Tense=Pqp|VerbForm=Fin|Voice=Act</td><td><em>کرده بودی, داده بودی, کشیده, نگاشته بودی, کرده بود</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=2|attachment=ISO|number=SING|tma=GEL</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Sub|Number=Sing|Person=2|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>کرده باشی, داشته باشی, مرده باشی, زیسته باشی, گفته باشی</em></td></tr>
  <tr><td>V ACT person=2|attachment=ISO|number=SING|tma=GES</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=2|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>می‌کردی, می‌خواستی, می‌آمدی, می‌رفتی, می‌توانستی</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=2|attachment=ISO|number=SING|tma=GN</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Sing|Person=2|Tense=Nar|VerbForm=Fin|Voice=Act</td><td><em>کرده‌ای, دیده‌ای, آمده‌ای, فروداده‌ای, مانده‌ای</em></td></tr>
  <tr><td>V ACT person=2|attachment=ISO|number=SING|tma=GS</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Sing|Person=2|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>کردی, بودی, دادی, پراندی, توانستی</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=2|attachment=ISO|number=SING|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>می‌کنی, داری, هستی, می‌خواهی, می‌نوشی</em></td></tr>
  <tr><td>V ACT person=2|attachment=ISO|number=SING|tma=HA</td><td>=&gt;</td><td>VERB</td><td>Mood=Imp|Number=Sing|Person=2|VerbForm=Fin|Voice=Act</td><td><em>کن, باش, بگو, بیا, بگذار</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=2|attachment=ISO|number=SING|tma=HEL</td><td>=&gt;</td><td>VERB</td><td>Mood=Sub|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>کنی, باشی, بگیری, داری, دهی</em></td></tr>
  <tr><td>V ACT person=2|attachment=NXT|number=PLUR|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Plur|Person=2|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>می‌شناسید</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=2|attachment=PRV|number=PLUR|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Plur|Person=2|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>ید, اید, یم</em></td></tr>
  <tr><td>V ACT person=2|attachment=PRV|number=SING|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>ی, یی, ای, ست</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=2|attachment=PRV|number=SING|tma=HA</td><td>=&gt;</td><td>VERB</td><td>Mood=Imp|Number=Sing|Person=2|VerbForm=Fin|Voice=Act</td><td><em>ی</em></td></tr>
  <tr><td>V ACT person=3|attachment=ISO|number=PLUR|tma=AY</td><td>=&gt;</td><td>VERB</td><td>Mood=Ind|Number=Plur|Person=3|Tense=Fut|VerbForm=Fin|Voice=Act</td><td><em>خواهند کرد, خواهند داد, خواهند زد, خواهند بود, خواهند داشت</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=3|attachment=ISO|number=PLUR|tma=GB</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Plur|Person=3|Tense=Pqp|VerbForm=Fin|Voice=Act</td><td><em>کرده بودند, داده بودند, گرفته بودند, آورده بودند, زده بودند</em></td></tr>
  <tr><td>V ACT person=3|attachment=ISO|number=PLUR|tma=GEL</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Sub|Number=Plur|Person=3|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>کرده باشند, داشته باشند, داده باشند, گرفته باشند, نداشته باشند</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=3|attachment=ISO|number=PLUR|tma=GES</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Plur|Person=3|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>می‌کردند, می‌دادند, می‌زدند, می‌گرفتند, می‌آمدند</em></td></tr>
  <tr><td>V ACT person=3|attachment=ISO|number=PLUR|tma=GN</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Plur|Person=3|Tense=Nar|VerbForm=Fin|Voice=Act</td><td><em>کرده‌اند, داده‌اند, گرفته‌اند, بوده‌اند, داشته‌اند</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=3|attachment=ISO|number=PLUR|tma=GNES</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Plur|Person=3|Tense=Nar|VerbForm=Fin|Voice=Act</td><td><em>می‌کرده‌اند, می‌خوانده‌اند, می‌موییده‌اند</em></td></tr>
  <tr><td>V ACT person=3|attachment=ISO|number=PLUR|tma=GS</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Plur|Person=3|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>کردند, بودند, دادند, داشتند, زدند</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=3|attachment=ISO|number=PLUR|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>می‌کنند, هستند, دارند, می‌دهند, می‌توانند</em></td></tr>
  <tr><td>V ACT person=3|attachment=ISO|number=PLUR|tma=HA</td><td>=&gt;</td><td>VERB</td><td>Mood=Imp|Number=Plur|Person=3|VerbForm=Fin|Voice=Act</td><td><em>نباشند, کنند, بیاشامید, بخورید, بزنید</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=3|attachment=ISO|number=PLUR|tma=HEL</td><td>=&gt;</td><td>VERB</td><td>Mood=Sub|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>کنند, باشند, بکنند, بدهند, دارند</em></td></tr>
  <tr><td>V ACT person=3|attachment=ISO|number=SING</td><td>=&gt;</td><td>VERB</td><td>Number=Sing|Person=3|Voice=Act</td><td><em>برنشانید</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=3|attachment=ISO|number=SING|tma=AY</td><td>=&gt;</td><td>VERB</td><td>Mood=Ind|Number=Sing|Person=3|Tense=Fut|VerbForm=Fin|Voice=Act</td><td><em>خواهد کرد, خواهد شد, خواهد بود, خواهد داد, خواهد آمد</em></td></tr>
  <tr><td>V ACT person=3|attachment=ISO|number=SING|tma=GB</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Sing|Person=3|Tense=Pqp|VerbForm=Fin|Voice=Act</td><td><em>کرده بود, داده بود, زده بود, آمده بود, گرفته بود</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=3|attachment=ISO|number=SING|tma=GEL</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Sub|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>کرده باشد, داشته باشد, داده باشد, نداشته باشد, زده باشد</em></td></tr>
  <tr><td>V ACT person=3|attachment=ISO|number=SING|tma=GES</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>می‌کرد, می‌زد, می‌داد, می‌آمد, می‌رفت</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=3|attachment=ISO|number=SING|tma=GN</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Sing|Person=3|Tense=Nar|VerbForm=Fin|Voice=Act</td><td><em>کرده است, کرده, آمده است, بوده است, بوده</em></td></tr>
  <tr><td>V ACT person=3|attachment=ISO|number=SING|tma=GNES</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Nar|VerbForm=Fin|Voice=Act</td><td><em>می‌کرده است, می‌دانسته, می‌کرده, می‌شوریده است, می‌شکافته است</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=3|attachment=ISO|number=SING|tma=GS</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>کرد, بود, داشت, داد, گفت</em></td></tr>
  <tr><td>V ACT person=3|attachment=ISO|number=SING|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>است, می‌کند, دارد, نیست, می‌دهد</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=3|attachment=ISO|number=SING|tma=HA</td><td>=&gt;</td><td>VERB</td><td>Mood=Imp|Number=Sing|Person=3|VerbForm=Fin|Voice=Act</td><td><em>کن, باشد, دارد, بده, نروید</em></td></tr>
  <tr><td>V ACT person=3|attachment=ISO|number=SING|tma=HEL</td><td>=&gt;</td><td>VERB</td><td>Mood=Sub|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>کند, باشد, بکند, دارد, دهد</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=3|attachment=NXT|number=PLUR|tma=GES</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Plur|Person=3|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>می‌انداختند</em></td></tr>
  <tr><td>V ACT person=3|attachment=NXT|number=PLUR|tma=GS</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Plur|Person=3|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>پذیرفتند</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=3|attachment=NXT|number=PLUR|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>ند, می‌برند</em></td></tr>
  <tr><td>V ACT person=3|attachment=NXT|number=SING|tma=GES</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>می‌کند</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=3|attachment=NXT|number=SING|tma=GS</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>کشاند</em></td></tr>
  <tr><td>V ACT person=3|attachment=NXT|number=SING|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>ست</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=3|attachment=PRV|number=PLUR|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>ند, اند, یند, ترند, اند </em></td></tr>
  <tr><td>V ACT person=3|attachment=PRV|number=SING|tma=AY</td><td>=&gt;</td><td>VERB</td><td>Mood=Ind|Number=Sing|Person=3|Tense=Fut|VerbForm=Fin|Voice=Act</td><td><em>ست, ید</em></td></tr>
  <tr style="background:lightgray"><td>V ACT person=3|attachment=PRV|number=SING|tma=GS</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Act</td><td><em>ست</em></td></tr>
  <tr><td>V ACT person=3|attachment=PRV|number=SING|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act</td><td><em>ست, ند, ام, اند, ی</em></td></tr>
  <tr style="background:lightgray"><td>V MODL attachment=ISO|number=SING|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Tense=Pres|VerbForm=Fin|VerbType=Mod</td><td><em>نمی‌توان, می‌توان</em></td></tr>
  <tr><td>V MODL attachment=ISO|number=SING|tma=HEL</td><td>=&gt;</td><td>VERB</td><td>Mood=Sub|Number=Sing|Tense=Pres|VerbForm=Fin|VerbType=Mod</td><td><em>باید, بایستی, بتوان</em></td></tr>
  <tr style="background:lightgray"><td>V MODL attachment=ISO|tma=GEL</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Sub|Tense=Past|VerbForm=Fin|VerbType=Mod</td><td><em>بایستی</em></td></tr>
  <tr><td>V MODL attachment=ISO|tma=GES</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Tense=Past|VerbForm=Fin|VerbType=Mod</td><td><em>می‌بایست, می‌شد, نمی‌شد</em></td></tr>
  <tr style="background:lightgray"><td>V MODL attachment=ISO|tma=GS</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Tense=Past|VerbForm=Fin|VerbType=Mod</td><td><em>نباید, بایستی, باید</em></td></tr>
  <tr><td>V MODL attachment=ISO|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Tense=Pres|VerbForm=Fin|VerbType=Mod</td><td><em>می‌توان, نمی‌توان, باید, نمی‌شود, می‌شود</em></td></tr>
  <tr style="background:lightgray"><td>V MODL attachment=ISO|tma=HEL</td><td>=&gt;</td><td>VERB</td><td>Mood=Sub|Tense=Pres|VerbForm=Fin|VerbType=Mod</td><td><em>باید, نباید, بتوان, بایستی, نمی‌توان</em></td></tr>
  <tr><td>V MODL attachment=NXT|tma=HEL</td><td>=&gt;</td><td>VERB</td><td>Mood=Sub|Tense=Pres|VerbForm=Fin|VerbType=Mod</td><td><em>باید</em></td></tr>
  <tr style="background:lightgray"><td>V MODL person=1|attachment=ISO|number=PLUR|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Plur|Person=1|Tense=Pres|VerbForm=Fin|VerbType=Mod</td><td><em>می‌توانیم</em></td></tr>
  <tr><td>V MODL person=1|attachment=ISO|number=SING|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin|VerbType=Mod</td><td><em>می‌توانم</em></td></tr>
  <tr style="background:lightgray"><td>V MODL person=2|attachment=ISO|number=SING|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin|VerbType=Mod</td><td><em>می‌توانی</em></td></tr>
  <tr><td>V MODL person=3|attachment=ISO|number=PLUR|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|VerbType=Mod</td><td><em>می‌توانند</em></td></tr>
  <tr style="background:lightgray"><td>V MODL person=3|attachment=ISO|number=SING|tma=GES</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|VerbType=Mod</td><td><em>می‌بایست, نمی‌بایستی, می‌بایستی, نمی‌شد</em></td></tr>
  <tr><td>V MODL person=3|attachment=ISO|number=SING|tma=GNES</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Nar|VerbForm=Fin|VerbType=Mod</td><td><em>می‌توانسته</em></td></tr>
  <tr style="background:lightgray"><td>V MODL person=3|attachment=ISO|number=SING|tma=GS</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|VerbType=Mod</td><td><em>باید</em></td></tr>
  <tr><td>V MODL person=3|attachment=ISO|number=SING|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|VerbType=Mod</td><td><em>باید, نباید, می‌توان, نمی‌تواند, می‌شود</em></td></tr>
  <tr style="background:lightgray"><td>V MODL person=3|attachment=ISO|number=SING|tma=HEL</td><td>=&gt;</td><td>VERB</td><td>Mood=Sub|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|VerbType=Mod</td><td><em>باید, می‌توان, نباید, بایستی, نمی‌شود</em></td></tr>
  <tr><td>V PASS attachment=ISO|number=SING|tma=GEL</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Sub|Number=Sing|Tense=Past|VerbForm=Fin|Voice=Pass</td><td><em>شده باشد</em></td></tr>
  <tr style="background:lightgray"><td>V PASS person=1|attachment=ISO|number=PLUR|tma=AY</td><td>=&gt;</td><td>VERB</td><td>Mood=Ind|Number=Plur|Person=1|Tense=Fut|VerbForm=Fin|Voice=Pass</td><td><em>نخواهیم شد</em></td></tr>
  <tr><td>V PASS person=1|attachment=ISO|number=PLUR|tma=GB</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Plur|Person=1|Tense=Pqp|VerbForm=Fin|Voice=Pass</td><td><em>شده بودیم</em></td></tr>
  <tr style="background:lightgray"><td>V PASS person=1|attachment=ISO|number=PLUR|tma=GES</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Plur|Person=1|Tense=Past|VerbForm=Fin|Voice=Pass</td><td><em>می‌شدیم, فرومی‌شدیم</em></td></tr>
  <tr><td>V PASS person=1|attachment=ISO|number=PLUR|tma=GN</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Plur|Person=1|Tense=Nar|VerbForm=Fin|Voice=Pass</td><td><em>شده‌ایم</em></td></tr>
  <tr style="background:lightgray"><td>V PASS person=1|attachment=ISO|number=PLUR|tma=GS</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Plur|Person=1|Tense=Past|VerbForm=Fin|Voice=Pass</td><td><em>شدیم, فراخوانده شدیم, انگیخته نشدیم, شده, نشدیم</em></td></tr>
  <tr><td>V PASS person=1|attachment=ISO|number=PLUR|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Plur|Person=1|Tense=Pres|VerbForm=Fin|Voice=Pass</td><td><em>می‌شویم, فرومی‌شویم, شده</em></td></tr>
  <tr style="background:lightgray"><td>V PASS person=1|attachment=ISO|number=PLUR|tma=HEL</td><td>=&gt;</td><td>VERB</td><td>Mood=Sub|Number=Plur|Person=1|Tense=Pres|VerbForm=Fin|Voice=Pass</td><td><em>شویم, نشویم</em></td></tr>
  <tr><td>V PASS person=1|attachment=ISO|number=SING|tma=AY</td><td>=&gt;</td><td>VERB</td><td>Mood=Ind|Number=Sing|Person=1|Tense=Fut|VerbForm=Fin|Voice=Pass</td><td><em>خواهم شد, درخواهم شد</em></td></tr>
  <tr style="background:lightgray"><td>V PASS person=1|attachment=ISO|number=SING|tma=GB</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Sing|Person=1|Tense=Pqp|VerbForm=Fin|Voice=Pass</td><td><em>شده بودم, شده بودیم, نشده بودم</em></td></tr>
  <tr><td>V PASS person=1|attachment=ISO|number=SING|tma=GES</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=1|Tense=Past|VerbForm=Fin|Voice=Pass</td><td><em>می‌شدم, نمی‌شدم</em></td></tr>
  <tr style="background:lightgray"><td>V PASS person=1|attachment=ISO|number=SING|tma=GN</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Sing|Person=1|Tense=Nar|VerbForm=Fin|Voice=Pass</td><td><em>شده‌ام</em></td></tr>
  <tr><td>V PASS person=1|attachment=ISO|number=SING|tma=GS</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Sing|Person=1|Tense=Past|VerbForm=Fin|Voice=Pass</td><td><em>شدم, نشدم, گذارده شدم</em></td></tr>
  <tr style="background:lightgray"><td>V PASS person=1|attachment=ISO|number=SING|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin|Voice=Pass</td><td><em>می‌شوم, می‌شود, نمی‌شوم</em></td></tr>
  <tr><td>V PASS person=1|attachment=ISO|number=SING|tma=HEL</td><td>=&gt;</td><td>VERB</td><td>Mood=Sub|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin|Voice=Pass</td><td><em>شوم, بشوم</em></td></tr>
  <tr style="background:lightgray"><td>V PASS person=2|attachment=ISO|number=PLUR|tma=AY</td><td>=&gt;</td><td>VERB</td><td>Mood=Ind|Number=Plur|Person=2|Tense=Fut|VerbForm=Fin|Voice=Pass</td><td><em>خواهید شد, فراخواهیدخواند</em></td></tr>
  <tr><td>V PASS person=2|attachment=ISO|number=PLUR|tma=GB</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Plur|Person=2|Tense=Pqp|VerbForm=Fin|Voice=Pass</td><td><em>نشده بودید</em></td></tr>
  <tr style="background:lightgray"><td>V PASS person=2|attachment=ISO|number=PLUR|tma=GEL</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Sub|Number=Plur|Person=2|Tense=Past|VerbForm=Fin|Voice=Pass</td><td><em>شده باشید</em></td></tr>
  <tr><td>V PASS person=2|attachment=ISO|number=PLUR|tma=GN</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Plur|Person=2|Tense=Nar|VerbForm=Fin|Voice=Pass</td><td><em>شده‌اید</em></td></tr>
  <tr style="background:lightgray"><td>V PASS person=2|attachment=ISO|number=PLUR|tma=GS</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Plur|Person=2|Tense=Past|VerbForm=Fin|Voice=Pass</td><td><em>شدید</em></td></tr>
  <tr><td>V PASS person=2|attachment=ISO|number=PLUR|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Plur|Person=2|Tense=Pres|VerbForm=Fin|Voice=Pass</td><td><em>می‌شوید, برگردانده می‌شوید</em></td></tr>
  <tr style="background:lightgray"><td>V PASS person=2|attachment=ISO|number=PLUR|tma=HA</td><td>=&gt;</td><td>VERB</td><td>Mood=Imp|Number=Plur|Person=2|VerbForm=Fin|Voice=Pass</td><td><em>نشوید, شوید</em></td></tr>
  <tr><td>V PASS person=2|attachment=ISO|number=PLUR|tma=HEL</td><td>=&gt;</td><td>VERB</td><td>Mood=Sub|Number=Plur|Person=2|Tense=Pres|VerbForm=Fin|Voice=Pass</td><td><em>شوید, نشوید, بشوید</em></td></tr>
  <tr style="background:lightgray"><td>V PASS person=2|attachment=ISO|number=SING|tma=GB</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Sing|Person=2|Tense=Pqp|VerbForm=Fin|Voice=Pass</td><td><em>پخته بودی</em></td></tr>
  <tr><td>V PASS person=2|attachment=ISO|number=SING|tma=GES</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=2|Tense=Past|VerbForm=Fin|Voice=Pass</td><td><em>می‌شدم</em></td></tr>
  <tr style="background:lightgray"><td>V PASS person=2|attachment=ISO|number=SING|tma=GN</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Sing|Person=2|Tense=Nar|VerbForm=Fin|Voice=Pass</td><td><em>نشده‌ای</em></td></tr>
  <tr><td>V PASS person=2|attachment=ISO|number=SING|tma=GS</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Sing|Person=2|Tense=Past|VerbForm=Fin|Voice=Pass</td><td><em>شدی</em></td></tr>
  <tr style="background:lightgray"><td>V PASS person=2|attachment=ISO|number=SING|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin|Voice=Pass</td><td><em>می‌شوی, شدی</em></td></tr>
  <tr><td>V PASS person=2|attachment=ISO|number=SING|tma=HA</td><td>=&gt;</td><td>VERB</td><td>Mood=Imp|Number=Sing|Person=2|VerbForm=Fin|Voice=Pass</td><td><em>شو</em></td></tr>
  <tr style="background:lightgray"><td>V PASS person=2|attachment=ISO|number=SING|tma=HEL</td><td>=&gt;</td><td>VERB</td><td>Mood=Sub|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin|Voice=Pass</td><td><em>نشوی, بشوی, شوی</em></td></tr>
  <tr><td>V PASS person=3|attachment=ISO|number=PLUR|tma=AY</td><td>=&gt;</td><td>VERB</td><td>Mood=Ind|Number=Plur|Person=3|Tense=Fut|VerbForm=Fin|Voice=Pass</td><td><em>خواهند شد, شدند, برانگیخته خواهند شد, تنیده خواهند شد</em></td></tr>
  <tr style="background:lightgray"><td>V PASS person=3|attachment=ISO|number=PLUR|tma=GB</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Plur|Person=3|Tense=Pqp|VerbForm=Fin|Voice=Pass</td><td><em>شده بودند, تابانده بودند, شده, پرداخته بودیم, نشده بودند</em></td></tr>
  <tr><td>V PASS person=3|attachment=ISO|number=PLUR|tma=GEL</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Sub|Number=Plur|Person=3|Tense=Past|VerbForm=Fin|Voice=Pass</td><td><em>شده باشند, خورده باشند, نشده باشند</em></td></tr>
  <tr style="background:lightgray"><td>V PASS person=3|attachment=ISO|number=PLUR|tma=GES</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Plur|Person=3|Tense=Past|VerbForm=Fin|Voice=Pass</td><td><em>می‌شدند, انداخته می‌شدند, خوانده می‌شدند, می‌شد, فرومی‌شدند</em></td></tr>
  <tr><td>V PASS person=3|attachment=ISO|number=PLUR|tma=GN</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Plur|Person=3|Tense=Nar|VerbForm=Fin|Voice=Pass</td><td><em>شده‌اند, شده, نوشته شده‌اند, ساخته شده‌اند, نشده‌اند</em></td></tr>
  <tr style="background:lightgray"><td>V PASS person=3|attachment=ISO|number=PLUR|tma=GS</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Plur|Person=3|Tense=Past|VerbForm=Fin|Voice=Pass</td><td><em>شدند, کشته شدند, شدیم, بازداشته شدند, رهانده شدند</em></td></tr>
  <tr><td>V PASS person=3|attachment=ISO|number=PLUR|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Pass</td><td><em>می‌شوند, شده, داده می‌شوند, زاده می‌شوند, گذارده می‌شوند</em></td></tr>
  <tr style="background:lightgray"><td>V PASS person=3|attachment=ISO|number=PLUR|tma=HA</td><td>=&gt;</td><td>VERB</td><td>Mood=Imp|Number=Plur|Person=3|VerbForm=Fin|Voice=Pass</td><td><em>شوید</em></td></tr>
  <tr><td>V PASS person=3|attachment=ISO|number=PLUR|tma=HEL</td><td>=&gt;</td><td>VERB</td><td>Mood=Sub|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Pass</td><td><em>شوند, شکسته شوند, شناخته شوند, تکانده شوند, بشوند</em></td></tr>
  <tr style="background:lightgray"><td>V PASS person=3|attachment=ISO|number=SING|tma=AY</td><td>=&gt;</td><td>VERB</td><td>Mood=Ind|Number=Sing|Person=3|Tense=Fut|VerbForm=Fin|Voice=Pass</td><td><em>خواهد شد, برآورده خواهد شد, آمیخته خواهد شد, بازتابیده خواهد شد, داده خواهد شد</em></td></tr>
  <tr><td>V PASS person=3|attachment=ISO|number=SING|tma=GB</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Sing|Person=3|Tense=Pqp|VerbForm=Fin|Voice=Pass</td><td><em>شده بود, نشده بود, ساخته شده بود, شده, بخشوده</em></td></tr>
  <tr style="background:lightgray"><td>V PASS person=3|attachment=ISO|number=SING|tma=GEL</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Sub|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Pass</td><td><em>شده باشد, چرانیده شده باشد, بسته شده باشد, شده, نشده باشد</em></td></tr>
  <tr><td>V PASS person=3|attachment=ISO|number=SING|tma=GES</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Pass</td><td><em>می‌شد, نمی‌شد, دیده می‌شد, گفته می‌شد, داده می‌شد</em></td></tr>
  <tr style="background:lightgray"><td>V PASS person=3|attachment=ISO|number=SING|tma=GN</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Sing|Person=3|Tense=Nar|VerbForm=Fin|Voice=Pass</td><td><em>شده است, شده, داده شده است, داده شده, گرفته شده است</em></td></tr>
  <tr><td>V PASS person=3|attachment=ISO|number=SING|tma=GNES</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Nar|VerbForm=Fin|Voice=Pass</td><td><em>می‌شده, برکشیده می‌شود, رانده می‌شده</em></td></tr>
  <tr style="background:lightgray"><td>V PASS person=3|attachment=ISO|number=SING|tma=GS</td><td>=&gt;</td><td>VERB</td><td>Aspect=Perf|Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Pass</td><td><em>شد, شده است, داده شد, شده, نشد</em></td></tr>
  <tr><td>V PASS person=3|attachment=ISO|number=SING|tma=H</td><td>=&gt;</td><td>VERB</td><td>Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Pass</td><td><em>می‌شود, نمی‌شود, داده می‌شود, دیده می‌شود, گفته می‌شود</em></td></tr>
  <tr style="background:lightgray"><td>V PASS person=3|attachment=ISO|number=SING|tma=HEL</td><td>=&gt;</td><td>VERB</td><td>Mood=Sub|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Pass</td><td><em>شود, بشود, نشود, داده شود, ورزیده شود</em></td></tr>
</table>