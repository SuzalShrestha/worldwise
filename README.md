# WorldWise Project

A map app for marking your visited destination anywhere in the world.

## My Notes For Future Reference

* installing eslint
  
```bash
  npm install eslint vite-plugin-eslint eslint-config-react-app --save-dev
  ```

* create a `.eslintrc.json` file in the root directory and add the following code

```javascript
{
    "extends":"react-app"
}
```

* add the following code in the `vite.config.js` file

```javascript
import eslint from 'vite-plugin-eslint';
export default defineConfig({
  plugins: [react(), eslint()],
});
```

* add react router dom

```bash
npm install react-router-dom
```
