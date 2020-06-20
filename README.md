### description

将blob格式的数据导出到本地

### 安装
```$xslt
npm install '@falseluffy/export-file'
```

### 使用

```$xslt
import exportFile from '@falseluffy/export-file'

exportFile(blob, filename, function() {
    alert('导出成功')
})

```

```$xslt
<script src="./export-file/src/index.js"></script>  

<script>
    exportFile(blob, filename, function() {
        alert('导出成功')
    })
</script>
```

```$xslt
const exportFile = require('@falseluffy/export-file')

exportFile(blob, filename, function() {
        alert('导出成功')
    })
```