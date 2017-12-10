# fis3Test

> 编译 fis3 release 输出到output文件夹

```javascript
fis.match('*.js', {
    deploy: fis.plugin('local-deliver', {
        to: './output'
    })
})
```