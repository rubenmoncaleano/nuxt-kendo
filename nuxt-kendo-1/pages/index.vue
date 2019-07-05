<template>
  <kendo-menu ref="menu1" id="menu1">
    <li>
      Item 1
      <ul>
        <li>
          Sub Item 1
          <ul>
            <li>Sub Item 1.1</li>
            <li>Sub Item 1.2</li>
            <li>Sub Item 1.3</li>
          </ul>
        </li>
        <li>Sub Item 2</li>
        <li>Sub Item 3</li>
      </ul>
    </li>
    <li>
      Item 2
      <ul>
        <li>Sub Item 1</li>
        <li>
          Sub Item 2
          <ul>
            <li>Sub Item 1.1</li>
            <li>Sub Item 1.2</li>
            <li>Sub Item 1.3</li>
          </ul>
        </li>
        <li>Sub Item 3</li>
      </ul>
    </li>
    <li>
      Item 3
      <ul>
        <li>Sub Item 1</li>
        <li>
          Sub Item 2
          <ul>
            <li>Sub Item 1.1</li>
            <li>Sub Item 1.2</li>
            <li>Sub Item 1.3</li>
          </ul>
        </li>
        <li>Sub Item 3</li>
      </ul>
    </li>
  </kendo-menu>
</template>

<script>
export default {
  head() {
    return {
      script: [
        { src: "https://code.jquery.com/jquery-1.12.4.min.js" },
        { src: "https://kendo.cdn.telerik.com/2017.3.913/js/kendo.all.min.js" },
        {
          src:
            "https://cdnjs.cloudflare.com/ajax/libs/babel-core/5.6.15/browser-polyfill.min.js"
        },
        { src: "https://unpkg.com/vue/dist/vue.min.js" },
        {
          src:
            "https://unpkg.com/@progress/kendo-layout-vue-wrapper/dist/cdn/kendo-layout-vue-wrapper.js"
        }
      ],
      link: [
        {
          src:
            "https://kendo.cdn.telerik.com/2017.3.913/styles/kendo.common.min.css"
        },
        {
          src:
            "https://kendo.cdn.telerik.com/2017.3.913/styles/kendo.default.min.css"
        }
      ]
    };
  }
};
</script>

