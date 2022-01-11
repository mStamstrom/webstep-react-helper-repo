## Difficulty dropdown levels

`const difficultyOptions = ["Any difficulty", "Easy", "Medium", "Hard"];`

## Dropdown render function

```
<select onChange={props.onChange}>
  {props.options.map((option) => (
    <option>{option}</option>
  ))}
</select>
```

## Javascript function commands

Funktion
const myFunction = () => {}

logga in console
console.log()

## React component commands

Skapa tom component

```
interface Props {
    myProp: string
}

export const myComponent = (props: Props) => {
return (<div></div>);
}
```

Skapa upp state
`const [value, setValue] = useState();`

## Input interface

interface Props extends React.InputHTMLAttributes<HTMLInputElement> {
label: string;
}

## Dropdown interface

interface Props extends React.SelectHTMLAttributes<HTMLSelectElement> {
label: string;
options: string[];
}

# Use preventdefault

const submitForm = (e: React.FormEvent) => {
e.preventDefault();
};

# Async/await

```
const myFunction = async (url: string) => {
const response = fetch(url)
return (await response).json()
}

const callApi = async () => {
await myFunction("http://test.com")
}
```
