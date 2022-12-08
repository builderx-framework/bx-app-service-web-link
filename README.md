## About @builderx-framework/bx-app-service-web

> **Note:** This repository contains link package for BuilderX web app.

## Installation

```shell
npm i @builderx-framework/bx-app-service-web-link
```

## Usage

We can have a link to pages like so:

```
import Link from "@builderx-framework/bx-app-service-web-link";

function Home() {
  return (
    <ul>
      <li>
        <Link href="/">Home</Link>
      </li>
      <li>
        <Link href="/about">About Us</Link>
      </li>
      <li>
        <Link href="/blog/hello-world">Blog Post</Link>
      </li>
    </ul>
  )
}

export default Home
```
