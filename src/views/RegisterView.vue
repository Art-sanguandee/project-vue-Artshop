<template>

<div class="contrainer">
  <div class="row">
  <form>
  <div class="register">

    <section class="h-100 h-custom" style="background-color: #8fc4b7;">
  <div class="container py-5 h-100">
    <div class="row d-flex justify-content-center align-items-center h-100">
      <div class="col-lg-8 col-xl-6">
        <div class="card rounded-3">
          <img src="https://mdbcdn.b-cdn.net/img/Photos/new-templates/bootstrap-registration/img3.webp"
            class="w-100" style="border-top-left-radius: .3rem; border-top-right-radius: .3rem;"
            alt="Sample photo">
          <div class="card-body p-4 p-md-5">
            <h3 class="mb-4 pb-2 pb-md-0 mb-md-5 px-md-2">Registration Info</h3>

            <form class="px-md-2">

              <div data-mdb-input-init class="form-outline mb-4">
              <div class="form-floating">
                      <input type="email" class="form-control" id="floatingInput" placeholder="name@example.com">
                      <label for="floatingInput">Name</label>
                    </div>
                    </div>

              <div class="row">
                <div class="col-md-6 mb-4">
                  <div data-mdb-input-init class="form-outline datepicker">
                    <div class="form-floating">
                      <input type="email" class="form-control" id="floatingInput" placeholder="name@example.com">
                      <label for="floatingInput">Select a date</label>
                    </div>
                  </div>
                </div>

                <div class="col-md-6 mb-4">
                  
                  <div class="form-floating">
                  <select data-mdb-select-init type="select" class="form-control" id="floatingInput" placeholder="name@example.com">
                    <option value="1" disabled>Gender</option>
                    <option value="2">Female</option>
                    <option value="3">Male</option>
                    <option value="4">Other</option>
        
                  </select>
                </div>
                </div>
              </div>

              <div class="mb-4">
                <div class="form-floating">
                  <select data-mdb-select-init type="select" class="form-control" id="floatingInput" placeholder="name@example.com">

                  <option value="1" disabled>Class</option>
                  <option value="2">Class 1</option>
                  <option value="3">Class 2</option>
                  <option value="4">Class 3</option>
                </select>

              </div>
              </div>
              <div class="row mb-4 pb-2 pb-md-0 mb-md-5">
                <div class="col-md-6">
                  <div class="form-floating">
                      <input type="email" class="form-control" id="floatingInput" placeholder="name@example.com">
                      <label class="form-label" for="form3Example1w">Registration code</label>
                  <div data-mdb-input-init class="form-outline">
                    
                  </div>
                  </div>

                </div>
              </div>

              <button type="submit" data-mdb-button-init data-mdb-ripple-init class="btn btn-success btn-lg mb-1">Submit</button>

            </form>

          </div>
        </div>
      </div>
    </div>
  </div>
</section>
    
  </div>
</form>
        </div>
    </div>
  
</template>
