<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>

<script>
  export default {
    name: 'Creator',
    data () {
      return {
        test: 'test',
        people: {
          1: {
            firstName: 'Артём',
            maidenName: null,
            lastName: 'Крючков',
            middleName: 'Александрович',
            isMan: true,
            birthDate: '1994-08-14T00:00:00.000',
            deathDate: null,
            biography: 'Биография',
            relationship: [{
              partner: 5,
              wedding: '2019-08-10T00:00:00.000'
            }],
            fatherId: null,
            motherId: 3,
            broSis: [2],
            children: []
          },
          2: {
            firstName: 'Елизавета',
            maidenName: null,
            lastName: 'Крючкова',
            middleName: 'Александровна',
            isMan: false,
            birthDate: '2002-01-30T00:00:00.000',
            deathDate: null,
            biography: 'Биография',
            fatherId: null,
            motherId: 3,
            broSis: [1],
            children: []
          },
          3: {
            firstName: 'Татьяна',
            lastName: 'Крючкова',
            maidenName: 'Кокорева',
            middleName: 'Николаевна',
            isMan: false,
            birthDate: '2072-08-27T00:00:00.000',
            deathDate: null,
            biography: 'Биография',
            relationship: [{
              partner: 4,
              wedding: '1994-03-12T00:00:00.000'
            }],
            fatherId: null,
            motherId: null,
            broSis: [],
            children: [1, 2]
          },
          4: {
            firstName: 'Александр',
            lastName: 'Крючков',
            maidenName: null,
            middleName: 'Александрович',
            isMan: true,
            birthDate: '2073-09-29T00:00:00.000',
            deathDate: null,
            biography: 'Биография',
            relationship: [{
              partner: 3,
              wedding: '1994-03-12T00:00:00.000'
            }],
            fatherId: null,
            motherId: null,
            broSis: [],
            children: [1, 2]
          },
        }
      }
    }
  }
</script>
