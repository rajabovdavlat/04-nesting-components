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


# 05. Event Bus

**Date:** July 02, 2026

### What I Learned

Today I learned how to use **Event Bus** in Vue 2 — a simple way for components to communicate with each other without using props and events.

### Key Concepts:

- Created a global Event Bus (`new Vue()`) in `main.js`
- Used `bus.$emit()` to send events
- Used `bus.$on()` to listen for events
- Understood when to use Event Bus (for non-parent/child communication)

### Example in this project:

- Clicking on the header changes the title
- The change is sent via Event Bus
- Footer receives the new title and updates automatically

### Important Notes:

- Event Bus is good for small to medium projects
- For larger applications, it's better to use Vuex or Pinia (state management)
- Always remember to clean up listeners with `$off()` if needed (to avoid memory leaks)

### Conclusion:

Event Bus is a simple and powerful pattern for sharing data between unrelated components. It's like a global messenger in your Vue application.

---

**Status:** Completed !!!
