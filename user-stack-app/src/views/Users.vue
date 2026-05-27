<template>
  <div class="container">
    <h3>Users</h3>
    <hr />
    <div class="d-flex justify-content-end my-4">
      <button type="button" class="btn btn-outline-secondary me-2">
        Add
      </button>
      <button type="button" class="btn btn-outline-secondary me-2">Edit</button>
      <button type="button" class="btn btn-outline-secondary me-2">Delete</button>

      <div class="search-box">
        <input
          type="text"
          class="search-input form-control"
          placeholder="  Search anything..."
        />
        <i class="fas fa-search search-icon"></i>
      </div>
    </div>
    <table class="table shadow">
      <thead>
        <tr>
          <th scope="col">#</th>
          <th scope="col">First</th>
          <th scope="col">Last</th>
          <th scope="col">Handle</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th scope="row">1</th>
          <td>Mark</td>
          <td>Otto</td>
          <td>@mdo</td>
        </tr>
        <tr>
          <th scope="row">2</th>
          <td>Jacob</td>
          <td>Thornton</td>
          <td>@fat</td>
        </tr>
        <tr>
          <th scope="row">3</th>
          <td colspan="2">Larry the Bird</td>
          <td>@twitter</td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<style>
.search-box {
    /* position: relative; */
    /* background: white;
    border-radius: 30px;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05); */
 /* transition: all 0.3s ease; */
}

.btn{
    border-radius: 30px;
    width: 100px;
    height: 30px;
    font-weight: 300;
    font-size: 14px;
}

.search-input {
    border: 2px solid #eee;
    border-radius: 30px;
    padding: 15px 25px;
    padding-right: 50px;
    width: 100%;
    height: 30px;
    /* transition: all 0.3s ease; */
}
.search-icon {
       
    position: absolute;
    top: 11.5%;
    right: 21%;
}

.table {
    color: rgb(140, 139, 139);
    font-weight: 300;
    font-size: 14px;
}
</style>