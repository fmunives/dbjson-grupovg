# dbjson-grupovg
v: 1.0
Información para testear datos del site

para poder usar este json puedes copiar este link de placeholderjson:

https://my-json-server.typicode.com/fmunives/dbjson-grupovg/courses

puedes usar el componente de axios e importarlo desde React. 
 ejem:
 
 usando yarn: yarn add axios
 importando en react: import axios from 'axios'
 
 Ejm en React usando clases y componente DidMount :
 
 componentDidMount = () => {
    axios
      .get(
        "https://my-json-server.typicode.com/fmunives/dbjson-grupovg/courses"
      )
      .then(response =>
        this.setState({
          courses: response.data
        })
      );
  };
 
 


