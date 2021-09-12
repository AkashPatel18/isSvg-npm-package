"# isSvg-npm-package"\
pass a firebase storage link and it will tell you the link is for svg image or not.
```
const isSvg = require('is-svg-firebase');

firebaseStorageURL = 'https://firebasestorage.googleapis.com/v0/b/blah-blah-project/o/0DBmVk1w31yQDUQFbWjM.svg?alt=media&token=78657e58-98ba-4b87-b9a2-3fd39dba6427'

let isSvgURL = isSvg(firebaseStorageURL)

console.log(isSvgURL)
```
 
