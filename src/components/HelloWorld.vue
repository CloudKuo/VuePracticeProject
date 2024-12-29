<template>
  <div class="HelloWorld">
    <div class="container">
      <div class="form row">
        <p>
          <button
            type="button"
            class="btn btn-primary col row-auto"
            data-bs-toggle="modal"
            data-bs-target="#testModal"
          >
            Launch demo modal
          </button>
        </p>
      </div>
    </div>

    <div class="modal fade" id="testModal">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="modal-header">
            <h5 class="modal-title">Modal title</h5>
            <button
              type="button"
              class="btn-close"
              data-bs-dismiss="modal"
              aria-label="Close"
            ></button>
          </div>
          <div class="modal-body">
            <div class="formg-roup">
              <label for="email">Your email</label>
              <input id="email" type="email" class="form-control" required />
            </div>
            <div class="formg-roup">
              <label for="password">Your password</label>
              <input
                id="password"
                type="password"
                class="form-control"
                required
              />
            </div>
          </div>
          <div class="modal-footer">
            <button
              type="button"
              class="btn btn-secondary"
              data-bs-dismiss="modal"
            >
              Close
            </button>
            <button type="button" class="btn btn-primary">Save changes</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
</script>

