# json-server
Typicode JSON Server

## Usage

### Posts

Request:

```bash
curl -s https://my-json-server.typicode.com/ruanbekker/json-server/posts
```

<details>
  <summary>Response</summary>
  
```json
[
  {
    "id": 1,
    "title": "Post 1"
  },
  {
    "id": 2,
    "title": "Post 2"
  },
  {
    "id": 3,
    "title": "Post 3"
  }
]
```
</details>

### Comments

Request:

```bash
curl -s https://my-json-server.typicode.com/ruanbekker/json-server/comments
```

<details>
  <summary>Response</summary>

```json
[
  {
    "id": 1,
    "body": "some comment",
    "postId": 1
  },
  {
    "id": 2,
    "body": "some comment",
    "postId": 1
  }
]
```
</details>

### Profile

```bash
curl -s https://my-json-server.typicode.com/ruanbekker/json-server/profile
```

<details>
  <summary>Response</summary>
  
```json
{
  "name": "typicode"
}
```

</details>

## Resource

- https://github.com/typicode/json-server
