# دفاتر Jupyter لـ "إنتاجية المياه ومحاسبة المياه باستخدام برنامج WaPOR" التدريبي المفتوح
! [] (http://www.fao.org/typo3temp/pics/93f49ce381.jpg)
## [شاهد الدورة الكاملة على IHE Delft OpenCourseWare] (https://ocw.un-ihe.org/course/view.php؟id=92&section=0)

المؤلفون: بيش تران ، أبيبي شكلا ، سليمان سيوم

<html>
  <head>
    <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"> <img alt = "ترخيص المشاع الإبداعي" style = "border-width: 0" src = "https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /> </a> <br /> هذا العمل مرخص بموجب <a rel = "License" href = "http://creativecommons.org/licenses/by-nc-sa/4.0/"> المشاع الإبداعي Attribution-NonCommercial-ShareAlike 4.0 International License </a>
  </head>
</html>

## محتويات

### الوحدة 1: المقدمة والاستخدام

- الوحدة الرابعة لتحليل البيانات المكانية WaPOR باستخدام حزم Python
    * تنزيل بيانات WaPOR النقطية
    * مقطع وإعادة أخذ العينات
    * حساب النقطية
- الوحدة 5 WaPOR API
    * احصل على فهرس وجدول البيانات المتاحة
    * احصل على نقطة ومنطقة زمنية متسلسلة
    * احصل على خطوط المسح والمحاصيل النقطية
    * احصل على بيانات نقطية مخصصة لإنتاجية المياه

### إعداد بيئة Python

** يجب عليك القيام بذلك في المرة الأولى التي تفتح فيها Jupyter Notebooks **

** الخطوة 1 **: قم بتنزيل ملف zipfile الخاص بالمستودع وفك ضغطه

أو

يجب تثبيت Clone in Git Bash ([Git] (https://git-scm.com/))

    >>> git clone https://github.com/wateraccounting/WAPOROCW.git


** الخطوة 2 **: افتح موجه Anaconda ، وقم بتغيير الدليل إلى مجلد **..\WAPOROCW-master**

    >>> cd ..PATH..\WAPOROCW-master\
    
** الخطوة 3 **: أنشئ بيئة جديدة من ملف environment.yml

    >>> conda env create
    
! [] (./create_env.PNG)

### بدء Jupyter Notebook

** الخطوة 1 **: تغيير الدليل إلى مجلد **..\WAPOROCW-master\notebooks_AR**

    >>> cd ..PATH..\WAPOROCW-master\notebooks_AR
 
** الخطوة 2 **: ثم تفعيل البيئة بالباقات المطلوبة

    >>> conda activate waporocw
  
** الخطوة 3 **: ابدأ دفتر jupyter

    >>> jupyter notebook
    
![](./activate_env.PNG)