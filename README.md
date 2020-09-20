# Mis-Custo-Hooks

Ejemplo de uso:

## useCounter

```
Const { counter, increment, decrement, reset } = useCounter(10);
```

useCounter() // recive un valor por defecto

## useFetch

```
const url = 'Aqui la ruta';
const { data: null, loadinig: true, error: null} = useFetch(url);
```

## useForm

```
const initialForm = {
    name: '',
    age: '',
    email: ''
};

const [ formValues, handelInputChange, reset ] = useForm( initialForm )

const { name, age, email } = formValues
```
