# caj2pdf.invoker
��� https://github.com/caj2pdf/caj2pdf �ļ��׷�װ����ʹC#�ܹ��Ϸ����ʹ�ã�����python3������μ�Դ��Ŀ

ʹ��ʱ��Ҫ��װ caj2pdf.invoker ���� runtime ������ǰֻ����windowsx64��ubuntux64�İ���

��Ŀ�������� `Python 3.3+`

- ԭʼ��Ŀ��ַ�� https://github.com/caj2pdf/caj2pdf
- jbig2dec��ַ�� https://github.com/ArtifexSoftware/jbig2dec
- PyPDF2��ַ�� https://github.com/py-pdf/PyPDF2
- mupdf ���ص�ַ�� https://www.mupdf.com/releases/index.html

### ���ʹ��

```C#
await Caj2PdfConverter.ConvertAsync("files/1.caj", "./out/1.pdf", default);
```