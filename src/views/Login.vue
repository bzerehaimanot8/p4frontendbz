<template>
  <div>
           <b-field label="Username"
            type="is-success"
            message="This username is available">
            <b-input value="johnsilver" maxlength="30"></b-input>
        </b-field>

        <b-field label="Password"
            type="is-warning"
            :message="['Password is too short', 'Password must have at least 8 characters']">
            <b-input value="123" type="password" maxlength="30"></b-input>
        </b-field>

  </div>
</template>

<script>


export default {
  name: 'Login'

}
</script>
