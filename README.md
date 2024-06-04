The background color is `#ffffff` for light mode and `#000000` app.get("/", (req, res) => {

  const user = {
    name: 'Laiza Medeiros',
    age: 26,
    birthday: '01/07',
    city: 'Rio de Janeiro, RJ',
    main_stack: ['Java/Spring', 'JavaScript', 'React(JS|Native)', '(My|Postgre)SQL' , '(cibersecurity)' , '(python)' , "(angular)' '(java)'],
    hobby: 'I love to play game, watch anime, series, coffe and code :)'
  };
  
  res.json(user);
});
