## ಪರಿಚಯ

ನೀವು ಸಂವಾದಾತ್ಮಕ ಬ್ಯಾಡ್ಜ್ ಮಾಡಲು ಹೊರಟಿದ್ದೀರಿ, ಅದು ನಿಮ್ಮ ಮನಸ್ಥಿತಿಯನ್ನು ನಿಮ್ಮ ಸ್ನೇಹಿತರಿಗೆ ತೋರಿಸುತ್ತದೆ.

** ಸೂಚನೆಗಳು **: ನೀವು ಇದನ್ನು ಆನ್‌ಲೈನ್‌ನಲ್ಲಿ ಓದುತ್ತಿದ್ದರೆ, ಸಂತೋಷದ ಮುಖವನ್ನು ಸೂಚಿಸಲು ಕೆಳಗಿರುವ ಮೈಕ್ರೊ:ಬಿಟ್ನಲ್ಲಿ ** ಎ ** ಮತ್ತು ** ಬಿ ** ದುಃಖದ ಮುಖವನ್ನು ತೋರಿಸಲು ಒತ್ತಿ.

<div class="trinket" style="width:400px;margin: 0 auto;">
<div style="position:relative;height:0;padding-bottom:81.97%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---run?id=_M6yLfbemfPUv" allowfullscreen="allowfullscreen" sandbox="allow-popups allow-scripts allow-same-origin" frameborder="0"></iframe></div>
</div>

### ಕ್ಲಬ್ ನಾಯಕರಿಗೆ ಹೆಚ್ಚು ಮಾಹಿತಿ

ನೀವು ಈ ಪ್ರಾಜೆಕ್ಟ್ಅನ್ನು ಮುದ್ರಿಸಬೇಕಾದರೆ, ದಯವಿಟ್ಟು [ಮುದ್ರಣ ಸ್ನೇಹಿ ಅನುವಾದವನ್ನು ](https://projects.raspberrypi.org/en/projects/interactive-badge/print)ಬಳಸಿ.

## \--- collapse \---

## title: ಕ್ಲಬ್ ನಾಯಕ ಟಿಪ್ಪಣಿಗಳು

## ಪರಿಚಯ:

ಈ ಯೋಜನೆಯಲ್ಲಿ, ಸಂವಾದಾತ್ಮಕ ಬ್ಯಾಡ್ಜ್ ಮಾಡುವ ಮೂಲಕ ಸೂಚನೆಗಳ ಅನುಕ್ರಮಗಳನ್ನು ಕಾರ್ಯಗತಗೊಳಿಸಲು ಇನ್ಪುಟ್ ಈವೆಂಟ್‌ಗಳನ್ನು ಹೇಗೆ ಬಳಸಬೇಕೆಂದು ಮಕ್ಕಳು ಕಲಿಯುತ್ತಾರೆ. Micro:bit ನಲ್ಲಿನ ಗುಂಡಿಗಳನ್ನು ಒತ್ತುವುದರಿಂದ ಪ್ರದರ್ಶಿಸಲಾದ ಚಿತ್ರ ಬದಲಾಗುತ್ತದೆ.

## ಸಂಪನ್ಮೂಲಗಳು

ಈ ಯೋಜನೆಗೆ [MakeCode (PXT)](http://jumpto.cc/pxt-new) microbit editor ಅನ್ನು ಉಪಯೋಗಿಸಿ.

ಈ ಪ್ರೋಜೆಕ್ಟಿನ ಪೂರ್ಣ ಆವೃತ್ತಿ ನಿಮಗೆ [makecode.microbit.org/#pub:90418-17495-16581-63753](https://makecode.microbit.org/#pub:90418-17495-16581-63753) ನಲ್ಲಿ ಸಿಗುತ್ತದೆ, ಹಾಗು ಸಂಕಲಿಸಲಾಗಿದೆ .hex ಫೈಲನ್ನು ಡೌನ್ಲೋಡ್ ಮಾಡಲು 'Download Project Materials' ಲಿಂಕ್ ಅನ್ನು ಒತ್ತಿರಿ, ಅಲ್ಲಿ ನಿಮಗೆ ಕೆಳಗೆ ತೋರಿಸಿದ ಫೈಲ್ಸ್ ಸಿಗುತ್ತದೆ:

* ಮೈಕ್ರೋಬಿಟ್-ಇಂಟರ್ಯಾಕ್ಟಿವ್-ಬ್ಯಾಡ್ಜ್.ಹೆಕ್ಸ

## ಕಲಿಕೆ ಉದ್ದೇಶಗಳು

* ಇನ್‌ಪುಟ್‌ಗಳು (`on button pressed`);
* ಅನುಕ್ರಮ ಸೂಚನೆಗಳು.

ಈ ಪ್ರಾಜೆಕ್ಟ್ [Raspberry Pi Digital Making Curriculum](http://rpf.io/curriculum) ಎಳೆಗಳಿಂದ ಕೆಳಗಿನ ಅಂಶಗಳನ್ನು ಒಳಗೊಂಡಿದೆ:

* [ಸರಳ ಪ್ರೊಗ್ರಾಂಗಳನ್ನು ರಚಿಸಲು ಮೂಲ ಪ್ರೋಗ್ರಾಮಿಂಗ್ ರಚನೆಗಳನ್ನು ಬಳಸಿ.](https://www.raspberrypi.org/curriculum/programming/creator)

## ಸವಾಲುಗಳು

* "ದುಃಖದ ಮುಖವನ್ನು ಪ್ರದರ್ಶಿಸುವುದು " - ಹೊಸ ಈವೆಂಟ್ ` ಗುಂಡಿ ಒತ್ತಿದಾಗ `ಕೋಡ್ ಸೇರಿಸುವುದು;
* "ನಿಮ್ಮ ಸ್ವಂತ ಸಂವಾದಾತ್ಮಕ ಬ್ಯಾಡ್ಜ್ ರಚಿಸಿ!" - ಈ ಪ್ರಾಜೆಕ್ಟ್ನಲ್ಲಿ ಕಲಿತ ಕೌಶಲ್ಯಗಳ ಬಲವರ್ಧನೆ.

\--- /collapse \---

## \--- collapse \---

## title: ಪ್ರೋಜೆಕ್ಟಿನ ವಸ್ತುಗಳು

## ಕ್ಲಬ್ ಮುಖಂಡರ ಸಂಪನ್ಮೂಲಗಳು

* [ಆನ್‌ಲೈನ್ ಪೂರ್ಣಗೊಂಡ ಪ್ರಾಜೆಕ್ಟ್](https://makecode.microbit.org/#pub:90418-17495-16581-63753)
* [.hex ಪ್ರಾಜೆಕ್ಟ್ ಫೈಲ್ಲ್ ಅನ್ನು ನಿಮ್ಮ micro:bit‌ಗೆ ವರ್ಗಾಯಿಸಲು](resources/microbit-Interactive-Badge.hex)

\--- /collapse \---