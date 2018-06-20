<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <title>Node Modules</title>
</head>
<body>
  <div id="app">
    <node-modules></node-modules>
  </div>

  <script src="https://unpkg.com/vue@2.3.3/dist/vue.js"></script>
  <script src="./dist/node-modules.min.js"></script>
  <script type="text/javascript">
  new Vue({
    el: "#app",
    components: {
      'node-modules': NodeModules.default
    }
  });
  </script>

</body>

</html>
