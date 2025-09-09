## Правовая информация

<style>
  /* --- Встроенные стили для колонок --- */
  .text{
   
    color: #3650e2ff;
    font-size:20px;
  }
  .two-columns-container {
    display: flex; /* Активируем Flexbox */
    flex-wrap: wrap; /* Позволяет колонкам переноситься на новую строку на узких экранах */
    gap: 40px;  /*Отступ между колонками */
    margin-bottom: 20px; /* Отступ под блоком колонок */
  }
  .column-item {
    flex: 1; /* Каждая колонка занимает равное пространство */
    min-width: 300px; /* Минимальная ширина колонки перед переносом на новую строку */
    padding:50px;
  }

  /* Медиа-запрос для адаптивности: на маленьких экранах колонки располагаются друг под другом */
  @media (max-width: 768px) {
    .two-columns-container {
      flex-direction: column; /* Изменяем направление на вертикальное */
    }
    .column-item {
      width: 100%; /* Каждая колонка занимает всю ширину */
      min-width: unset; /* Сбросить минимальную ширину */
    }
  }
  /* --- Конец встроенных стилей --- */
</style>

<div class="two-columns-container">
  <div class="column-item">
    <div class = "text">


[Политика конфиденциальности](politics.md)

</div>

  </div>
  <div class="column-item">
    
<div class = "text">

 [Публичная оферта](public-oferta.md)

</div>


  </div>

