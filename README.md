### Changing Compiler from Overleaf
* Sometimes for certain languages, classes and packages it may be necessary to use a different compiler like xelatex than the default pdflatex. We have to set XeLatex instead of PdfLatex for using fontspec package.</br>

	* To change the compiler, simply click into the left hand menu </br>
	![First Image](/images/first.png)

	* Click on the Compiler menu under Settings </br>
	![Second Image](/images/second.png)


### Download any Bengali Font
[https://www.omicronlab.com/bangla-fonts.html](Free Bangla Fonts Download)
</br>
I'm using Kalpurush. If you can take kalpurush.ttf from this repository.


### Add the following code snippet

```tex
\usepackage{fontspec}
\setmainfont{Times New Roman}
\newfontface{\bn}{kalpurush.ttf}
```
	
### Bangla Writing



```tex
\bn{অনেক আশা করে লিভারপুল ছেড়ে বার্সেলোনায় যোগ দিয়েছিলেন ব্রাজিল তারকা ফিলিপ কুতিনহো। দেড় বছর পর এখন সেই কুতিনহোই বার্সার মূল একাদশে জায়গা পান না। কুতিনহোকে বিক্রি করে দেওয়ার সর্বাত্মক চেষ্টা চালিয়ে যাচ্ছে বার্সেলোনা। কুতিনহোর পরবর্তী ক্লাব হিসেবে উচ্চারিত হচ্ছে লিভারপুলের নামও।}
```
