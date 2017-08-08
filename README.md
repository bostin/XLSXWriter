Fork from [mk-j/PHP_XLSXWriter](https://github.com/mk-j/PHP_XLSXWriter)

移入到命名空间：
```
namespace Bostin\Office\Excel;
```


添加了一个方法：
```
use Bostin\Office\Excel\XLSXWriter;

$data = array(
    array('year','month','amount'),
    array('2003','1','220'),
    array('2003','2','153.5'),
);

$writer = new XLSXWriter();
$writer->writeSheet($data);
$writer->outputToBrowser('output.xlsx'); // 即通过浏览器下载xlsx文件
```



