## File

### Constructor

```python
File(file_path)
```

| Parameter | Type   | Default | Description                                                  |
| --------- | ------ | ------- | ------------------------------------------------------------ |
| file_path | string |         | The absolute path or relative path of the file. If using a relative path, it must include `.` or `/`. |

### Attributes

<table>
    <tr>
    	<td><code>File.content</code></td>
        <td>Return the entire content of the file.</td>
    </tr>
    <tr>
    	<td><code>File.full_name</code></td>
        <td>Return the name of the file.</td>
    </tr>
    <tr>
    	<td><code>File.name</code></td>
        <td>Return the name of the file without the file extension.</td>
    </tr>
    <tr>
    	<td><code>File.ext</code></td>
        <td>Return the file extension of the file.</td>
    </tr>
</table>


### Operation

#### File.rewrite(content)

Rewrite the entire content of the file. 

#### File.append(content)

Append content at the end of file content.

#### File.delete()

Delete file.