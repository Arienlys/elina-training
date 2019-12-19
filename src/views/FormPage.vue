<template>
  <div class="form">
    <form>
      <adresse>
        <fieldset>
          <legend>Titre :</legend>
          <input type="checkbox" id="mr" name="title" value="mr" checked />
          <label for="coding">Mr</label>
          <input type="checkbox" id="mrs" name="title" value="mrs" />
          <label for="coding">Mrs</label>
          <input type="checkbox" id="ms" name="title" value="ms" />
          <label for="music">Ms</label>
        </fieldset>
        <br />
        <label
          >Civic number:
          <input type="number" id="cnumber" required />
        </label>
        <br />
        <label
          >Name:
          <input type="text" id="name" required />
        </label>
        <br />
        <label
          >Surname:
          <input type="text" id="surname" required />
        </label>
        <br />
        <label
          >Zip Code:
          <input type="number" id="zcode" required />
        </label>
        <br />
        <label
          >City:
          <input type="text" id="city" required />
        </label>
        <br />
        <label
          >Country:
          <input type="text" id="country" required />
        </label>
        <br />
        <label
          >Message box:
          <textarea id="mbox" rows="7" required> </textarea>
        </label>
      </adresse>
      <br /><br />
      <button type="submit">SEND THE NOUGAT!</button>
    </form>
  </div>
</template>

<script>
export default {
  name: "form"
};
</script>
