<template>
  <tr>
    <td>
      <table id="head-table">
        <tr>
          <td>
            <table id="name-table" class="name-table">
              <tr>
                <td align="right">Сюр Юлия, Р3233</td>
              </tr>
            </table>
          </td>
        </tr>
        <tr>
          <td>
            <table id="variant-table" class="variant-table">
              <tr>
                <td>
                  <div id="var" align="right">Вариант 3394</div>
                </td>
              </tr>
            </table>
          </td>
        </tr>
      </table>
    </td>
  </tr>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>
#name-table {
  width: 100%;
  border-spacing: 7px;
}

.name-table {
  background-color: #99004C;
}

.variant-table {
  background-color: #99004C;
}

#variant-table {
  width: 100%;
  font-size: 20px;
  margin: auto;
  border-spacing: 5px;
}

</style>
