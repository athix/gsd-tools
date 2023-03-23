<template>
  <q-page>
    <div class="q-pa-md row items-start justify-evenly q-gutter-md">
      <q-card>
          <q-card-section class="bg-primary text-white text-center">
            <div class="text-h6">Create A GSD ID</div>
          </q-card-section>

          <q-separator />

          <q-card-section>
            <q-input
              filled
              label="Summary"
            />
            <br>
            <q-input
              filled
              autogrow
              label="Details"
            />
            <br>
            <p>Affected</p>

          </q-card-section>

          <q-card-actions align="right">
            <q-btn flat>Submit</q-btn>
          </q-card-actions>
      </q-card>
    </div>
  </q-page>
</template>

<script>
export default {
  // name: 'PageName',
}
</script>
