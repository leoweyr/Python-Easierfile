## File

### Constructor

```python
File(filePath)
```

| Parameter | Type   | Default | Description                                                  |
| --------- | ------ | ------- | ------------------------------------------------------------ |
| filePath  | string |         | The absolute path or relative path of the file. If using a relative path, it must include `.` or `/`. |

### Attributes

<table>
    <tr>
    	<td><code>File.content</code></td>
        <td>Return the entire content of the file.</td>
    </tr>
</table>

### Operation

#### File.Rewrite(content)

Rewrite the entire content of the file. 

#### File.Append(content)

Append content at the end of file content.

#### File.Delete()

Delete file.