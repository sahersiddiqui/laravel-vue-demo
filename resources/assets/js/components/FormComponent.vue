<template>
    <div class="col-md-4">
        <form>
            <div class="form-group">
                <textarea 
                    class="form-control" 
                    rows="8" cols="8" 
                    maxlength="130" 
                    required>
                </textarea>
            </div>
            <div class="form-group">
                <button class="btn btn-primary">
                    Tweet
                </button>
            </div>
        </form>  
        <App/>      
    </div>
</template>
<script>
import App from './App.vue'

export default {
  components: {
    App
  }
}
</script>