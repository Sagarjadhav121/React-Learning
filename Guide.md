<h1>React Component:</h1>
<p>
React component are reusable UI block basically they are javascript functions that returns markup
Component always start with capital letter unlike HTML tag they are in small letters.
Example:
<code>
function MyButton() {
  return (
    <button>I'm a button</button>
  );
}
</code>
We use this component for e.g. MyButton() into another component.

<h2>How to Use this coponent</h2>
<code>
export default function MyApp() {
  return (
    <div>
      <h1>Welcome to my app</h1>
      <MyButton />  <---- Here you can see how we used it 
      
    </div>
  );
}
<p>The export default keywords specify the main component in the file</p>
</code>
</p>
