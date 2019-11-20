<template>
  <div class="about">
    <form method="post" action="contact/send">
      <h1>Contact
        <div class="form-group"><label>Name</label><input class="form-control" name="name"
                                                          placeholder="your name here"></div>
        <div class="form-group"><label>Email</label><input class="form-control" name="email"
                                                           placeholder="your email here"></div>
        <div class="form-group"><label>Message</label><textarea class="form-control" name="msg"
                                                                placeholder="send us your thoughts"></textarea>
        </div>
        <button class="btn btn-default" type="submit">Submit</button>
      </h1>
    </form>
  </div>
</template>
