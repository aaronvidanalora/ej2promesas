const direccionURL = 'https://pokeapi.co/api/v2/pokemon';

//2.0
async function mostrarTarjetas(datosJson){
    document.querySelector('#listaPokemons').innerHTML += `
        <div class="col-md-2">
            <div class="card shadow">
                <img src="${datosJson.sprites.front_default}" class="card-img-top" alt="${datosJson.name}">
                <div class="card-body">
                    <h5 class="card-title text-capitalize">${datosJson.name}</h5>
                    <div class="card-text">ID: ${datosJson.id}</div>
                    <div class="card-text">Tipo: ${datosJson.types.map(tipo => tipo.type.name).join(', ')}</div>
                    <div class="card-text">Peso: ${datosJson.weight}</div>
                    <div class="card-text">Altura: ${datosJson.height}</div>
                </div>
            </div>
        </div>
        `;
}

//  2.1 
document.querySelector('#btn1').addEventListener('click', async (evento) => {
    evento.preventDefault()
    document.querySelector('#listaPokemons').innerHTML = ''

    try {
        const inicioTiempo = new Date().getTime()

        for (let i = 1; i <= 12; i++) {
            let respuesta = await fetch(direccionURL + '/' + i)
            const datos = await respuesta.json()
            await mostrarTarjetas(datos)
        }

        const finalTiempo = new Date().getTime()
        const duracion = finalTiempo - inicioTiempo

        document.querySelector('#tiempo1').innerHTML = `TIEMPO: ${duracion} milisegundos`
    } catch (error) {
        console.error(error)
    }
})

//  2.2 
document.querySelector('#btn2').addEventListener('click', (evento) => {
    evento.preventDefault()
    document.querySelector('#listaPokemons').innerHTML = ''
    
    const inicioTiempo = new Date().getTime()
    
    fetch(`https://pokeapi.co/api/v2/pokemon/1`)
    .then(res => res.json())
    .then(resJSON => {

        mostrarTarjetas(resJSON)

        fetch(`https://pokeapi.co/api/v2/pokemon/2`)
        .then(res2 => res2.json())
        .then(resJSON2 => {

            mostrarTarjetas(resJSON2)

            fetch(`https://pokeapi.co/api/v2/pokemon/3`)
            .then(res3 => res3.json())
            .then(resJSON3 => {
    
                mostrarTarjetas(resJSON3)
                
                fetch(`https://pokeapi.co/api/v2/pokemon/4`)
                .then(res4 => res4.json())
                .then(resJSON4 => {
        
                    mostrarTarjetas(resJSON4)
                    
                    fetch(`https://pokeapi.co/api/v2/pokemon/5`)
                    .then(res5 => res5.json())
                    .then(resJSON5 => {
            
                        mostrarTarjetas(resJSON5)
                        
                        fetch(`https://pokeapi.co/api/v2/pokemon/6`)
                        .then(res6 => res6.json())
                        .then(resJSON6 => {
                
                            mostrarTarjetas(resJSON6)
                            
                            fetch(`https://pokeapi.co/api/v2/pokemon/7`)
                            .then(res7 => res7.json())
                            .then(resJSON7 => {
                    
                                mostrarTarjetas(resJSON7)
                                
                                fetch(`https://pokeapi.co/api/v2/pokemon/8`)
                                .then(res8 => res8.json())
                                .then(resJSON8 => {
                        
                                    mostrarTarjetas(resJSON8)
                                    
                                    fetch(`https://pokeapi.co/api/v2/pokemon/9`)
                                    .then(res9 => res9.json())
                                    .then(resJSON9 => {
                            
                                        mostrarTarjetas(resJSON9)
                                        
                                        fetch(`https://pokeapi.co/api/v2/pokemon/10`)
                                        .then(res10 => res10.json())
                                        .then(resJSON10 => {
                                
                                            mostrarTarjetas(resJSON10)
                                            
                                            fetch(`https://pokeapi.co/api/v2/pokemon/11`)
                                            .then(res11 => res11.json())
                                            .then(resJSON11 => {
                                    
                                                mostrarTarjetas(resJSON11)
                                                
                                                fetch(`https://pokeapi.co/api/v2/pokemon/12`)
                                                .then(res12 => res12.json())
                                                .then(resJSON12 => {
                                        
                                                    mostrarTarjetas(resJSON12)
                                                    
                                                    const finalTiempo = new Date().getTime()
                                                    const duracion = finalTiempo - inicioTiempo
                                                    document.querySelector('#tiempo2').innerHTML = `TIEMPO: ${duracion} milisegundos`
                                                
                                                })
                                                .catch(err => console.log(err))
                
                                            })
                                            .catch(err => console.log(err))
            
                                        })
                                        .catch(err => console.log(err))
        
                                    })
                                    .catch(err => console.log(err))
    
                                })
                                .catch(err => console.log(err))
    
                            })
                            .catch(err => console.log(err))
                
                        })
                        .catch(err => console.log(err))
            
                    })
                    .catch(err => console.log(err))
        
                })
                .catch(err => console.log(err))
    
            })
            .catch(err => console.log(err))
    
        })
        .catch(err => console.log(err))
    
    })
    .catch(err => console.log(err))
})

// Exercici 2.3 Promise.All
document.querySelector('#btn3').addEventListener('click', async (evento) => {
    evento.preventDefault()
    document.querySelector('#listaPokemons').innerHTML = ''

    const inicioTiempo = new Date().getTime()

    const arrayPokemons = []
    for (let i = 0; i < 12; i++) {

        arrayPokemons[i] = fetch(`https://pokeapi.co/api/v2/pokemon/${i + 1}`).then(res => res.json())

    }
    
    const respuesta = await Promise.all(arrayPokemons)

    for (let i = 0; i < 12; i++) {

        mostrarTarjetas(respuesta[i])

    }

    const finalTiempo = new Date().getTime()
    const duracion = finalTiempo - inicioTiempo

    document.querySelector('#tiempo3').innerHTML = `TIEMPO: ${duracion} milisegundos`
})
