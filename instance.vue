import { getCurrentInstance } from "vue";
export default {
  setup() {
    // accessible inside setup function
    const instance = getCurrentInstance();
    console.log(instance);
  },
};
