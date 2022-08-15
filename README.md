
- https://linktr.ee/farkadadnan
-  By:Farkad Adnan فرقد عدنان - 
 - E-mail: farkad.hpfa95@gmail.com 
- inst : farkadadnan 
- #farkadadnan , #farkad_adnan , فرقد عدنان# 
* facebook : https://www.facebook.com/profile.php?id=100002145048612
* instagram:  https://www.instagram.com/farkadadnan/
* linkedin : https://www.linkedin.com/in/farkad-adnan-499972121/
 <p>
 <a href='https://mobile.twitter.com/farkadadnan'>
        <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/farkadadnan?label=%40farkadadnan&style=social" alt='Twitter' align="center"/>
    </a>
</p>

* شرح على اليوتيوب  
- https://www.youtube.com/watch?v=KtMigezhp54


# ABSTRACT

- في الألعاب ، تتحرك الكيانات ويجب أن تجد طرقها إلى مواقع مختلفة. يجب أن تكون هذه الطرق خالية من الاصطدامات وطبيعية ويتم حسابها بسرعة كبيرة. يعد هذا تحديًا كبيرًا والعديد من الألعاب تحل هذا باستخدام نقاط الطريق المحسوبة مسبقًا أو البرمجة النصية أو الطرق البسيطة والسريعة التي تعتمد على البحث الشبكي أو الحقول المحتملة. غالبًا ما يغشون أو يقبلون حقيقة أن الشخصيات تمشي عبر الأشياء. تصبح المشكلة أكثر تعقيدًا عندما يجب أن تتحرك الكيانات في الألعاب في مجموعات. يجب أن يتصرفوا كما تفعل مجموعة طبيعية ، لكن تقنيات التدفق التي غالبًا ما يتم استغلالها لهذا الغرض يمكن أن تؤدي إلى نتائج غير متوقعة وغير مرغوب فيها.
- In games entities move around and must find their routes to various locations. These routes must be collision free, natural, and computed very fast. This is a major challenge and many games solve this by using precomputed waypoints, scripting, or simple but fast methods based on grid search or potential fields. Also very often they cheat or accept the fact that characters walk through objects. The problem becomes even more complicated when entities in games must move in groups. They should behave as a natural group does, but the flocking techniques that are often exploited for this can lead to rather unexpected and unwanted results.

 ![3333](https://user-images.githubusercontent.com/35774039/184294991-62bc189d-edb4-422d-af0b-6ed3af685867.PNG)
![33](https://user-images.githubusercontent.com/35774039/184293750-d7608cfd-84d3-4b50-b54d-5ab57e0ee5a8.PNG)


- يعد تخطيط المسار ، الذي يُطلق عليه أيضًا اسم المسار أو تخطيط الحركة ، عنصرًا حاسمًا في ألعاب الكمبيوتر. يحدث تخطيط المسار في العديد من الأماكن في الألعاب. من الواضح أن الكيانات التي يتحكم فيها الكمبيوتر يجب أن تجد طرقها إلى مواقع مختلفة لأداء إجراءات معينة. ولكن أيضًا الصورة الرمزية التي يتحكم فيها اللاعب يجب أن تجد مسارات تجنب الاصطدام ؛ على وجه الخصوص عندما يكون التحكم في الصورة الرمزية غير مباشر. وأخيرًا ، يجب أن تتحرك الكاميرا التي يراقب اللاعب من خلالها عالم اللعبة.
- Path planning, also termed pathing or motion planning is a crucial ingredient in computer games. Path planning occurs at many places in games. Clearly, computer controlled entities must find their routes to various locations to perform certain actions. But also the avatar controlled by the player must find collision avoiding paths; in particular when avatar control is indirect. And finally the camera through which the player observes the game world must move around.

# A corridor for a path 
![sas](https://user-images.githubusercontent.com/35774039/184292039-27e32d93-cce4-4ca8-92cf-9b1197fe3dc8.PNG)


# Determine the path of the body within the game
 Determine the path of the body within the game through several algorithms and using VFH technology and determine the path.
 
 # [Play Online ](https://farkadadnan.github.io/).
* https://farkadadnan.github.io/

![farkadadnan](https://user-images.githubusercontent.com/35774039/184148611-8460971b-5626-4388-8961-9c2fc6abd8fc.gif)

![22](https://user-images.githubusercontent.com/35774039/184293842-55c41733-2b4f-4e36-8404-a1563a3413d3.PNG)
![11](https://user-images.githubusercontent.com/35774039/184293845-a4e138dd-3865-4282-aeba-1804f09f5a30.PNG)


# How it works
- محرك الفيزياء المخصص
تعمل اللعبة بمحرك فيزيائي مبسط يعتمد على كشف اصطدام الصندوق المحيط بمحاذاة المحور. جميع الكائنات المادية في هذه اللعبة إما مربعات أو مربعات مربعة محاذية للمحور.  .

- محرر خرائط مخصص
يتم تضمين المعلومات حول الخريطة المادية في JSON يسمى الرسم البياني المشهد الذي يتم تحميل اللعبة على statup. لقد أنشأت هذا الملف باستخدام محرر خرائط مخصص ، أقوم بترميزه لغرض وحيد هو صنع هذه اللعبة. ابحث عن الكود هنا في مستودع منفصل.

- تحديد المواقع اليدوي للكاميرا
يعد تحريك الكاميرا لدعم لعبة منصات ثلاثية الأبعاد تحديًا ، كان علي مواجهته بمفردي منذ أن استخدمت محركًا مخصصًا للفيزياء. .

- التحسين التلقائي
اللعبة قابلة للعب من الهاتف المحمول متوسط ​​المدى إلى سطح المكتب عالي النطاق. لدعم هذه القدرة على التكيف ، تتكيف اللعبة مع قدرة الجهاز في وقت التشغيل.

- Custom physics engine
The game works with a simplistic physics engine based on axis-aligned bounding box collision detection. All the physic objects in this game are either boxes or axis-aligned square tiles.  

- Custom map editor
The information about the physical map is contained in an JSON called sceneGraph that the game loads on statup. I created this file using a custom map editor, that I coding for the sole purpose of making this game.  

- Manual camera positioning
Moving the camera to support a 3D platformer game is a challenge, that I had to face on my own since I used a custom physics engine.  

- Automatic optimization
The game is playable from mid-range mobile to high-range desktop. To support this adaptability, the game adapt itself to the device capability at runtime.  
 
# Take advice from Grandma and Grandpa
![شس](https://user-images.githubusercontent.com/35774039/184701364-a9a3e3a5-5444-4e29-8122-3b6da86f2fd6.PNG)


# REFERENCES 

-  Bohlin, R. and L. Kavraki (2000). Path planning using lazy prm. In Proc. IEEE Int. Conf. on Robotics and Automation, pp. 521–528.
-  Boor, V., M. Overmars, and A. van der Stappen . The gaussian sampling strategy for probabilistic roadmap planners. In Proc. IEEE Int. Conf. on Robotics and Automation, pp. 1018–1023. 
-  Branicky, M., S. Lavalle, K. Olson, and L. Yang (2001). Quasi randomized path planning. In Proc. IEEE Int. Conf. on Robotics and Automation. 
- DeLoura, M. (Ed.) (2000). Game Programming Gems 1. Charles River Media. 
- Holleman, C. and L. Kavraki (2000). A framework for using the workspace medial axis in prm planners. In Proc. IEEE Int. Conf. on Robotics and Automation, pp. 1408–1413. 
- Hsu, D., T. Jiang, J. Reif, and Z. Sun (2003). The bridge test for sampling narrow passages with probabilistic roadmap planners. In Proc. IEEE Int. Conf. on Robotics and Automation.
- Isto, P. (2002). Constructing probabilistic roadmaps with powerful local planning and path optimization. In IEEE/RSJ Int. Conf. on Intelligent Robots and Systems, pp. 2323–2328. 
- Kamphuis, A. and M. H. Overmars (2004). Finding paths for coherent groups using clearance. In Eurographics/ACM SIGGRAPH Symposium on Computer Animation, pp. 19–28.
