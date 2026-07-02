# 04. Nesting Components + Props

**Date:** July 02, 2026

### What I Learned

Today I practiced **Nesting Components** and **Props** in Vue 2.

I built a small "Vue Ninjas" website where:
- `App.vue` is the parent component
- `Header.vue`, `Ninjas.vue`, and `Footer.vue` are child components
- Data (`ninjas` array) is passed from parent to child component using **Props**

### Key Concepts:

- How to create and nest components
- How to pass data from parent to child using `props`
- Registering components in the `components` option
- Using `v-for`, `v-show`, and click events inside child component
- Scoped styles + modern design

### Main Conclusion:

**Props** allow us to pass data from a parent component down to a child component. This is one of the most important ways components communicate in Vue.

This example shows clean component architecture:
- Parent (`App.vue`) holds the data
- Child (`Ninjas.vue`) receives data via props and displays it

---

**Technologies Used:**
- Vue 2 Components
- Props (one-way data flow)
- Scoped CSS

**Status:** Completed !!!
