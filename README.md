<h2>Motivation</h2>
<p>In <a href='https://github.com/NathanKr/post-css-playground'>post-css-playground</a>, you need to install the packages postcss and postcss-cli and call postcss in the package.json script. You do this to invoke the plugins in postcss.config.js</p>
<p>But in vite part of this is done out of the box, i.e., you do not need to install the packages postcss and postcss-cli, and you do not need to call postcss in package.json</p>

<h2>Installation</h2>

```
pnpm i
```


<h2>Usage</h2>

View the page

```
npm run dev
```

Create build version

```
npm run build
```


<h2>Points of interest</h2>
<ul>
<li> There is no need to use nanocss explicitly because vite minimizes the CSS out of the box. simply do 'npm run build' and look inside the dist/assets directory</li>
<li> No need to use postcss-preset-env explicitly to translate nesting to format known to the old browser. do 'npm run build' and look inside the dist/assets directory</li>
</ul>
