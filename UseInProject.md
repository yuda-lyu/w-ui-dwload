### use code in `mUI.mjs`
```
import WUiDwload from 'w-ui-dwload/src/WUiDwload.mjs'

//WUiDwload
let mUIdws = WUiDwload(vo, {
    keyFunDownloadFileById: '$fapi.downloadFileById',
    keyFunUpdateLoading: '$ui.updateLoading',
    keyFunAlert: '$alert',
})
// console.log('mUIdws', mUIdws)

let mUI = {

    // downloadPic,
    // downloadTable,
    // downloadLtdt,
    // downloadFile,
    ...mUIdws,

}
```

