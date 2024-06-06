<script></script>
<template>
  <div class="container">
    <form>
      <div class="mb-3">
        <input
          type="text"
          class="form-control"
          id="eventTitle"
          placeholder="Titre de l'évènement"
        />
      </div>

      <div class="mb-3">
        <input
          list="event-type"
          id="eventType"
          name="eventType"
          placeholder="Type de l'évènement"
        />

        <datalist id="event-type">
          <option value="Festif"></option>
          <option value="Conférence"></option>
          <option value="Sport"></option>
        </datalist>
      </div>

      <div class="mb-3">
        <input
          type="text"
          class="form-control"
          id="postAuthor"
          placeholder="Votre nom"
        />
      </div>

      <div class="mb-3">
        <input type="date" class="form-control" id="eventDate" />
      </div>

      <div class="mb-3">
        <input
          type="textarea"
          class="form-control"
          id="eventDescription"
          placeholder="Description de l'évènement"
        />
      </div>

      <div class="mb-3">
        <input
          type="text"
          class="form-control"
          id="eventImage"
          placeholder="url de l'image de l'évènement"
        />
      </div>

      <button type="submit" class="btn btn-primary">Ajouter</button>
    </form>
  </div>
</template>
<style></style>
