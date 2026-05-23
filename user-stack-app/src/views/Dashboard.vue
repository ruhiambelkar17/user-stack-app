<template>
  <div class="dashboard-container">
    <div class="dashborad">
      <div class="row">
        <div class="col">
          <form>
            <div class="mb-3">
              <label for="exampleInputEmail1" class="form-label"
                >Email address</label
              >
              <input
                type="email"
                class="form-control"
                id="exampleInputEmail1"
                aria-describedby="emailHelp"
              />
              <div id="emailHelp" class="form-text">
                We'll never share your email with anyone else.
              </div>
            </div>
            <div class="mb-3">
              <label for="exampleInputPassword1" class="form-label"
                >Password</label
              >
              <input
                type="password"
                class="form-control"
                id="exampleInputPassword1"
              />
            </div>
            <div class="mb-3 form-check">
              <input
                type="checkbox"
                class="form-check-input"
                id="exampleCheck1"
              />
              <label class="form-check-label" for="exampleCheck1"
                >Check me out</label
              >
            </div>
            <button type="submit" class="btn">Submit</button>
          </form>
        </div>
      </div>
    </div>
    <!-- <div class="dashborad tile-text">
      <div class="row">
        <div class="col">Admin view</div>
      </div>
    </div> -->
  </div>
</template>

<style>
.dashboard-container {
  color: white;
  width: 100%;
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 24px;
  background-image: url("@/assets/images/dashboard-bg.avif");
  background-size: cover;
  background-position: center;
}

.dashborad {
  height: 400px;
  background-color: #0f211d;
  width: 500px;
  border-radius: 10px;
  display: flex;
  align-items: center;
  justify-content: center;
  /* margin-right: 50px; */
}
.dashborad:hover {
  background-color: #a8b78d;
}
.tile-text {
  font-size: 80px;
}

.btn {
  background-color: #a8b78d;
}
</style>
