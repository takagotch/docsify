### docsify
---
https://github.com/docsifyjs/docsify

```
npm i docsify-cli -g
docsify init ./docs
docsify serve docs

cd docs && python -m SimpleHTTPServer 3000
```

```js
window.$docsify = {
  el: '#main'
}

window.$docsify = {
  loadSidebar: true
}

window.$docsify = {
  loadSidebar: true,
  alias: {
    '/.*/_sidebar.md': '/_sidebar.md'
  }
}

window.$docsify = {
  loadsidebar: true,
  subMaxLevel: 2
}

window.$docsify = {
  coverpage: ['/', '/zh-cn/']
};

window.$docsify = {
  coverpage: {
    '/': 'cover.md',
    '/zh-cn/': 'cover.md'
  }
};

window.$docsify = {
  repo: 'docsifyjs/docsify',
  maxLevel: 3,
  coverpage: true
}

window.$docsify = {
  el: '#app'
};

window.$docsify = {
  repo: 'docsifyjs/docsify',
  repo: 'https://github.com/docsifyjs/docsify/'
};

window.$docsify = {
  maxLevel: 4
};

window.$docsify = {
  loadNavbar: true
  loadNavbar: 'nav.md'
};

window.$docsify = {
  loadSidebar: true,
  loadSidebar: 'summary.md'
};

window.$docsify = {
  subMaxLevel: 2
};

window.$docsify = {
  auto2top: true
};

window.$docsify = {
  homepage: 'home.md',
  homepage: 'https://raw.githubusercontent.com/docsifyjs/docsify/master/README.md'
};

widow.$docsify = {
  basePath: '/path/',
  basePath: 'https://docsify.js.org',
  basePath: 'https://raw.githubusercontent.com/ryanmdermott/clean-javascript/master/'
};

window.$docsify = {
  coverpage: true,
  coverpage: 'cover.md',
  coverpage: ['/', '/zh-cn/'],
  coverpage: {
    '/': 'cover.md',
    '/zh-cn/': 'cover.md'
  }
};

window.$docsify = {
  logo: '/_media/icon.svg'
};

window.$docsify = {
  name: 'docsify'
};

window.$docsify = {
  nameLink: '/',
  nameLink: {
    '/zh-cn/': '/zh-cn/',
    '/': '/'
  }
};

window.$docsify = {
  markdown: {
    smartypants: true,
    renderer: {
      link: funciton(){
      }
    }
  },
  markdown: funciton(marked, renderer){
    return marked;
  }
};

window.$docsify = {
  themeColor: '#3F51B5'
};

window.$docsify = {
  alias: {
    '/foo/(+*)': '/bar/$1',
    '/zh-cn/changelog': '/changelog',
    '/changelog': 'https://raw.githubusercontent.com/docsifyjs/docsify/master/CHANGELOG',
    '/.*/_sidebar.md': '/_sidebar.md'
  }
};

window.$docsify = {
  loadSidebar: true,
  autoHeader: true
};

window.$docsify = {
  executeScript: true
};

console.log(2333)

window.$docsify = {
  noEmoji: true
};

window.$docsify = {
  mergeNavbar: true
};

window.$docsify = {
  formatUpdated: '{MM}/{DD} {HH}:{mm}',
  formatUpdated: function(time){
    return time;
  }
};

window.$docsify = {
  externalLinkTarget: '_self'
};

window.$docsify = {
  routerMode: 'history'
};

window.$docsify = {
  noCompileLinks: ['/foo', '/bar/.*']
};

window.$docsify = {
  onlyCover: false
};

window.$docsify = {
  requestHeaders: {
    'x-token': 'xxx'
  }
};

window.$docsify = {
  ext: '.md'
};

window.$docsify = {
  fallbackLanguages: ['fr', 'de']
};

window.$docsify = {
  notFoundPage: true
};

window.$docsify = {
  notFoundPage: 'my404.md'
};

window.$docsify = {
  notFoundPage: {
    '/': '_404.md',
    '/de': 'de/_404.md'
  }
};

window.$docsify = {
  notFoundPage: {
    '/': '_404.md',
    '/de': 'de/_404.md'
  }
};
```

```
```


