# home
*強調*
This is a regular paragraph.

<table>
    <tr>
        <td>Foo</td><td>Foo</td><td>Foo</td>
    </tr>
    <tr>
        <td>ABC</td><td>ABC</td><td>ABC</td>
    </tr>

</table>

This is another regular paragraph.


This is an H1
=============

This is an H2
-------------


# This is an H1

## This is an H2

###### This is an H6

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
> 
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.


> ## This is a header.
> 
> 1.   This is the first list item.
> 2.   This is the second list item.
> 
>> Here's some example code:
>>
>>     return shell_exec("echo $input | $markdown_script");



無序清單使用星號、加號或是減號作為清單標記：

*   Red
*   Green
*   Blue
等同於：

+   Red
+   Green
+   Blue
也等同於：

-   Red
-   Green
-   Blue



有序清單則使用數字接著一個英文句點：

1.  Bird
2.  McHale
3.  Parish
很重要的一點是，你在清單標記上使用的數字並不會影響輸出的HTML結果，上面的清單所產生的HTML標記為：

<ol>
<li>Bird</li>
<li>McHale</li>
<li>Parish</li>
</ol>

*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
viverra nec, fringilla in, laoreet vitae, risus.
*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
Suspendisse id sem consectetuer libero luctus adipiscing.



*   Bird

*   Magic


<hr/>

* * *

***

*****

- - -

---------------------------------------


This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.
*single asterisks*

_single underscores_

**double asterisks**

__double underscores__


<http://example.com/>
