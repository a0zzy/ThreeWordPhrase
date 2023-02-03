
<a href="https://threewordphrase.carbondev.cf/">
    <img alt="Three Word Phrase" src="https://github.com/CleverCarpet/threewordphrase/blob/main/logo.png?raw=true" width="100" />
</a>

# Three Word Phrase

Need a random phrase made of three random words? Look no futher.

This is a very basic tool. Don't expect to much.

## Badges

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)


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
| `exactly` | `number` | `3` | How Many Strings to Generate |
| `minlength` | `string` | `none` | Minimum Length of Each Word |
| `maxlength` | `string` | `none` | Maximum Length of Each Word |
| `words` | `number` | `1` | How Many Words Per Each String |
| `format` | `string` | `beginning` | How to Format The Words  |

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
 - **Word Length Options**

    ```
    Maximum Strings Per Generation: 10
    ```

    ```
    Smallest Minimum: 2
    ```

    ```
    Largest Maximum: 20
    ```
    
    ```
    Maximum Words Per String: 5
    ```


#### generate(exactly, minlength, maxlength, words, format)

Generates a phrase with random words, using custom parameters


## Tech Stack

**Client Requirements:** JSON Parsing

**Server:** Node, Random-Words


## Support

For support, submit a contact request on my [Portfolio](https://cleverportfolio.carbondev.cf).

