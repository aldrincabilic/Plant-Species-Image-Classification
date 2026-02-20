# Plant-Species-Image-Classification

##Teachable Machine: https://teachablemachine.withgoogle.com/models/937aD8eSN/

##Drive link: https://drive.google.com/drive/folders/1WglyGos-yIOotcPLC3Sc6iu3QQnN3AKJ?usp=drive_link

# 🌿 B. Plant Species Section

This section presents the 20 selected tropical medicinal plants used in the image classification project.

---

## 🌱 Plant Gallery

<table>
<tr>
<td align="center">
<img src="Images/pan.jpg" width="200"><br>
<b>Ulasimang Bato</b><br>
<i>Peperomia pellucida</i><br>
Small succulent herb traditionally used for joint pain.
</td>

<td align="center">
<img src="Images/cu.jpg" width="200"><br>
<b>Curry Leaf</b><br>
<i>Murraya koenigii</i><br>
Aromatic shrub widely used in cooking and herbal medicine.
</td>

<td align="center">
<img src="images/kakawate.jpg" width="200"><br>
<b>Kakawate</b><br>
<i>Gliricidia sepium</i><br>
Fast-growing tree used as fencing and shade plant.
</td>

<td align="center">
<img src="images/gotu-kola.jpg" width="200"><br>
<b>Gotu Kola</b><br>
<i>Centella asiatica</i><br>
Creeping herb known for memory and wound support.
</td>
</tr>

<tr>
<td align="center">
<img src="images/serpentina.jpg" width="200"><br>
<b>Serpentina</b><br>
<i>Rauvolfia serpentina</i><br>
Medicinal plant traditionally used for blood pressure.
</td>

<td align="center">
<img src="images/chinese-leeks.jpg" width="200"><br>
<b>Chinese Leeks</b><br>
<i>Allium tuberosum</i><br>
Perennial herb used as vegetable and medicine.
</td>

<td align="center">
<img src="images/kamote-tops.jpg" width="200"><br>
<b>Kamote Tops</b><br>
<i>Ipomoea batatas</i><br>
Young sweet potato leaves rich in antioxidants.
</td>

<td align="center">
<img src="images/siling-labuyo.jpg" width="200"><br>
<b>Siling Labuyo</b><br>
<i>Capsicum frutescens</i><br>
Spicy chili plant common in Filipino cuisine.
</td>
</tr>

<tr>
<td align="center">
<img src="images/atsuete.jpg" width="200"><br>
<b>Atsuete</b><br>
<i>Bixa orellana</i><br>
Produces red seeds used as natural food coloring.
</td>

<td align="center">
<img src="images/mabolo.jpg" width="200"><br>
<b>Mabolo</b><br>
<i>Diospyros blancoi</i><br>
Velvet apple native to the Philippines.
</td>

<td align="center">
<img src="images/bibhitaki.jpg" width="200"><br>
<b>Bibhitaki</b><br>
<i>Terminalia bellirica</i><br>
Tree with fruits used in traditional medicine.
</td>

<td align="center">
<img src="images/shatavari.jpg" width="200"><br>
<b>Shatavari</b><br>
<i>Asparagus racemosus</i><br>
Climbing plant with medicinal roots.
</td>
</tr>

<tr>
<td align="center">
<img src="images/ashwagandha.jpg" width="200"><br>
<b>Ashwagandha</b><br>
<i>Withania somnifera</i><br>
Traditional medicinal shrub.
</td>

<td align="center">
<img src="images/guduchi.jpg" width="200"><br>
<b>Guduchi</b><br>
<i>Tinospora cordifolia</i><br>
Climbing plant used for immune support.
</td>

<td align="center">
<img src="images/alagaw.jpg" width="200"><br>
<b>Alagaw</b><br>
<i>Premna odorata</i><br>
Philippine medicinal shrub for cough remedies.
</td>

<td align="center">
<img src="images/malabar-nut.jpg" width="200"><br>
<b>Malabar Nut</b><br>
<i>Justicia adhatoda</i><br>
Leaves used for respiratory health.
</td>
</tr>

<tr>
<td align="center">
<img src="images/kratom.jpg" width="200"><br>
<b>Kratom</b><br>
<i>Mitragyna speciosa</i><br>
Tropical tree native to Southeast Asia.
</td>

<td align="center">
<img src="images/ageratum.jpg" width="200"><br>
<b>Ageratum</b><br>
<i>Ageratum conyzoides</i><br>
Small flowering plant common in tropical regions.
</td>

<td align="center">
<img src="images/kava.jpg" width="200"><br>
<b>Kava</b><br>
<i>Piper methysticum</i><br>
Root used in ceremonial herbal preparations.
</td>

<td align="center">
<img src="images/bitter-leaf.jpg" width="200"><br>
<b>Bitter Leaf</b><br>
<i>Vernonia amygdalina</i><br>
Shrub known for its medicinal bitter leaves.
</td>
</tr>
</table>

##Reflection Questions:

###Answer the following questions based on your experience:

####1. How did the number of images per class affect your model’s accuracy?
    #####Answer: Ang kadaghan sa images per class adunay dako nga epekto sa accuracy sa model. Sa akong case, naggamit ko og kapin sa 300 images per plant species, nga mas taas kaysa minimum requirement nga 250. Tungod ani, mas nakat-on ang model sa lain-laing anggulo, lighting, ug hitsura sa tanom. Resulta ani, mas taas ang confidence score ug mas sakto ang prediction sa model. Kung gamay ra ang images, mas taas ang chance nga mag-misclassify ang model tungod sa kulang nga training data.

####2. Which plant species were most commonly misclassified and why?
    ####Answer: Ang mga plant species nga parehas og porma sa dahon o parehas og kolor mao ang mas dali ma-misclassify. Pananglitan, ang ubang herbal plants nga parehas og green leaves ug shape mahimong maglibog ang model sa pag distinguish nila. Kini nahitabo tungod kay ang visual features sa ilang dahon parehas, ug usahay parehas usab ang background sa images. Ang similarity sa features mao ang main reason sa misclassification.
    
####3. How did changing the epochs, batch size, or learning rate affect the training results?
    ####Answer: Ang paggamit og 50 epochs nakatabang sa model nga mas makakat-on ug mas mo-improve ang accuracy over time. Ang batch size nga 16 naghatag og balance sa training speed ug performance. Ang learning rate nga 0.001 nakatabang sa stable nga learning process ug nakapugong sa sudden errors sa model. Kung taas kaayo ang learning rate, mahimong dili stable ang training, ug kung gamay ra kaayo ang epochs, dili makakat-on og tarong ang model.
    
####4. What challenges did you encounter during dataset collection and labeling?
    ####Answer: Usa sa main challenges mao ang pag pangita og daghang high-quality images nga klaro ug walay watermark. Lisod usab pangitaon ang images nga lain-lain ang anggulo ug lighting. Dugang pa, kinahanglan sigurohon nga sakto ang labeling sa kada plant species aron malikayan ang training errors. Ang pag organize sa images sa sakto nga classes nanginahanglan usab og oras ug effort.
    
####5. If you were to improve your model, what specific changes would you make and why?
    ####Answer: Kung akong i-improve ang model, magdugang ko og mas daghang images per class aron mas makakat-on ang model sa mas daghang variations sa plant species. Pwede usab nako usbon ang training parameters sama sa pag increase sa epochs aron mas ma improve ang accuracy. Dugang pa, mag gamit ko og mas diverse nga dataset nga adunay lain-lain nga backgrounds ug lighting conditions aron mas mahimong robust ug accurate ang model sa real-world situations.
