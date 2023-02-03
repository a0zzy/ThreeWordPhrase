
## Generator API Reference

```http
  https://threerandomwords.carboncdn.cf
```

#### Get all items

```http
  GET /api/generate
```

| Parameter | Type     | Default     | Description                |
| :-------- | :------- | :------- | :------------------------- |
| `exactly` | `number` | `3` | How Many Words to Generate |
| `maxlength` | `string` | `none` | Max Length of Each Word |
| `wordsperstring` | `number` | `1` | How Many Words Per Each String |
| `uppercase` | `string` | `beginning` | How to Format The Words  |

 - **Formating Options**

    ```
    none (No Formatting)
    ```

    ```
    beginning (First Letter of Word Uppercase)
    ```

    ```
    complete (Full Word Uppercase)
    ```


#### generate(exactly, maxlength, wordsperstring, uppercase)

Generates a phrase with random words, using custom parameters

