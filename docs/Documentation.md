

### Class: \jc21\FileList

| Visibility | Function |
|:-----------|:---------|
| public | <strong>get(</strong><em>string</em> <strong>$directory</strong>, <em>string</em> <strong>$type=`'both'`</strong>, <em>string</em> <strong>$order=`'name'`</strong>, <em>string</em> <strong>$direction=`'asc'`</strong>, <em>mixed/int</em> <strong>$limit=null</strong>, <em>array</em> <strong>$fileExtensions=array()</strong>)</strong> : <em>array</em><br /><em>Return the listing of a directory</em> |
| public | <strong>getLastItemCount()</strong> : <em>int</em><br /><em>Return the last listing count of items</em> |
| public | <strong>getLastSize()</strong> : <em>int</em><br /><em>Return the last listing size in bytes</em> |
| public | <strong>setFilterCallback(</strong><em>string/array</em> <strong>$object</strong>)</strong> : <em>void</em><br /><em>Sets the Filter Callback</em> |
| protected | <strong>getExtension(</strong><em>string</em> <strong>$file</strong>)</strong> : <em>string</em><br /><em>Returns the extension of a file, lowercase</em> |
| protected | <strong>sort(</strong><em>array</em> <strong>$items</strong>, <em>string</em> <strong>$type=`'both'`</strong>, <em>string</em> <strong>$by=`'name'`</strong>, <em>string</em> <strong>$direction=`'asc'`</strong>)</strong> : <em>array</em><br /><em>Order the results of a directory listing</em> |

