## File

### Constructor

```python
File(file_path, is_auto_create, is_occupy)
```

| Parameter      | Type   | Default | Description                                                  |
| -------------- | ------ | ------- | ------------------------------------------------------------ |
| file_path      | string |         | The absolute path or relative path of the file.              |
| is_auto_create | bool   | True    | Whether to automatically create the file if it does not exist. |
| is_occupy      | bool   | True    | Whether to enable file lock.                                 |

### Attributes

<table>
    <tr>
    	<td><code>File().content</code></td>
        <td>Return the entire content of the file.</td>
    </tr>
    <tr>
    	<td><code>File().info</code></td>
        <td>Return a dict of file attribute information.</br>● path: the absolute path of the file</br>● dir_path: the absolute path of the directory where the file is located</br>● full_name: the name of the file</br>● name: the name of the file without file extension</br>● ext: the extension of the file</br>● encoding: the encoding of the file</td>
    </tr>
	<tr>
		<td><code>File().status</code></td>
        <td>Return a dict of file status information.</br>● file_lock: whether file lock is on</br>● exist: whether the file exist</td>
	</tr>
</table>

### Operation

#### File().create()

Create file.

#### File().delete()

Delete file.

#### File().rewrite(content)

Rewrite the entire content of the file. 

#### File().append(content)

Append content at the end of file content.
