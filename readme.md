### demo01

- Like backboneJs, need to initial a component by new Vue. Attributes include el, data, computed, methods

##### Some directives

- v-bind : bind data in view and model. v-bind:class="{class: condition}"
- v-if : conditional rendering
- v-for : loop element
- v-on:event : add event to DOM
- v-model: two-way binding

- v-html: render data as html in DOM

The part after directive can access directly the attribute in data and methods.

##### Component

- Define component: Vue.component(name, {}) The name is not allowed to use Uppercase, we must render a component inside a declared vue app.
- Component has 'template' arribute with html
- Component has 'props' attribute for using in template
- When we bind a property to a component, it is not showing in DOM, but App Vue can get the property.

### demo02

- Lifecycle hook: created, mounted, updated, destroyed

### demo 03

- pass prop to component: need to initial in the props in component intialization. pass parameter directly in component or use v-bind
- pass event from child to parent: use emit and v-on the event name
- use v-model in component (bind input in component with the model): v-bind and emit input in component intialization, need to define in props
