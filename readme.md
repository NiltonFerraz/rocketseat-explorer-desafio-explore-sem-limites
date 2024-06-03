Para colocar img dentro do input

             <div class="input-container">
                        <img src="./assets/person.svg" class="placeholder-image">
                        <input type="text" class="input-field" placeholder="        Seu nome">
                      </div>

.input-container {
    position: relative;
    width: 300px;
    /* Ajuste conforme necessário */
}

.input-field {
    width: 100%;
    padding: 10px;
    font-size: 16px;
}

.placeholder-image {
    position: absolute;
    top: 50%;
    left: 10px;
    transform: translateY(-50%);
    width: 20px;
    /* Ajuste conforme necessário */
    height: 20px;
    /* Ajuste conforme necessário */
} 