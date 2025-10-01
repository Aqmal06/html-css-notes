# html-css-notes
HTML Properties\
-> text element? merupakan element special dalam text\
-> <strong> bold dalam text\
-> <u> underline\
-> <span> -> default p, tapi boleh modify dalam css\
Image dan Search box\
-> <img src"path_name">\
-> <input type="code" placeholder="code"">

CSS Grid\
-> display:grid (hanya terpakai setiap display:inline-block)\
-> grid-template-columns: Ypx/Xfr\
-> column-gap: (bersebelahan)\
-> row-gap: (atas bawah)\
-> target pada main element, bukan pada sub element

CSS Flexbox\
-> display: flex; (merupakan inline-block untuk flex)\
-> flex-direction: row; (make sure item display bersebelahan)\
-> flex: 1; (function seperti fr, free size)\
-> align-items: center (untuk pastikan div kekal berada di tgh walaupun heigh berubah)\
-> justify-content; (adjust kedudukan display) start/space-between/etc

CSS Position (Digunakan untuk create header dan sidebar)\
-> position: fixed; (code untuk bagi element stay apabila scroll)\
-> top: 0;\
-> left 0;\
-> bottom: 0;/height: px; (Gunakan height untuk header)\
-> right: 0;/width: px; (Gunakan width untuk sidebar kiri)

Position Relative dan Position obsolute\
-> position relative still display content normally, tapi dengan ada element position obsolute dalam position relative, element position obsolute boleh di manipulate\
-> ukuran position obsolute berdasarkan element position relative, bukan pada page\
-> z-index; (Tentukan element mana perlu display dahulu) (Higher value means element akan display berbanding default value)

CSS Features\
-> element{} manipulate kesemua yang terkandung dalam hood element\
-> .class element{} target specific class\
-> .class .class{} target sub class dalam specific class
