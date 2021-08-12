#useForm

ejemplo de uso

```
const initialForm = {
    name:'',
    age:0,
    email:'',
};
const[values, handleInputChange, reset] = useForm(initialForm);
```

Suponiendo que el archivo donde se llama es este y se tiene un campo llamado searchText en el formulario

```
const [values, handleInputChange, reset] = Useform({
    searchText: '',
  });
  const { searchText } = values;
```
