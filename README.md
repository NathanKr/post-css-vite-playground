<h2>Motivation</h2>
<p>In <a href='https://github.com/NathanKr/post-css-playground'>post-css-playground</a> you need to install the packages postcss and postcss-cli and call postcss in the package.json script. You do this to invoked the plugins in postcss.config.js</p>
<p>But in vite part of this is done out of the box i.e. you dont need to install the packages postcss and postcss-cli and you dont need to call postcss in package.json</p>

<h2>Installation</h2>

```
pnpm i
```


<h2>Usage</h2>

View the page

```
npm run dev
```

create build version

```
npm run build
```


<h2>Points of interest</h2>
<ul>
<li>no need to use nanocss explictly because vite minimize the css out of the box. simply do 'npm run build' and look inside dist/assets directory</li>
<li>no need to use postcss-preset-env explictly to tranlsate nesteing to format known to old browser. simply do 'npm run build' and look inside dist/assets directory</li>
</ul>