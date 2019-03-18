<template>
  <div>
    <div class="contacts">
      <div class="cntainer">
          <div class="row">
              <div class="col-8">Напишите нам и мы с вами обязательно свяжемся
                  <p>Ваше имя:</p>
                  <div class="form-control"></div> 
                  <p>Телефон:</p>
                  <div class="form-control"></div>
                  <p>E-mail:</p>
                  <div class="form-control"></div>
                  <p>Ваш вопрос:</p>
                  <div class="form-control"></div>
                  <button type="button" class="btn btn-primary">Отправить</button>
              </div>
              
              <div class="col-4"><h3>Наши контакты</h3>
              <p> <h5>Телефон:</h5> +7 (912) 345 67 89 </p>
              <p> <h5>E-mail:</h5> info@mail.ru </p>
              <p> <h5>Адрес:</h5> Нижний Новгород, ул. Родионова д 168 </p>

              </div>
          </div>
      </div>
    </div>
  </div>
  
</template>

<script>


export default {
  name: "Contacts",
  components: {
  },
  data() {
    return {};
  }
};
</script>
    
<style>
    .contacts{
        position: absolute;
        background: rgb(129, 137, 184);
        margin: 10px;
        height: 82%;
        width: 99%;
        border-radius: 5px;
    }
    .form-control{
        margin: 0 10px 10px 10px
    }

</style>
