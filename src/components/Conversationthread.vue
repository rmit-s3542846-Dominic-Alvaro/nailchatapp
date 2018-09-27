<template>
<div class="column is-6 message hero is-fullheight" id="message-pane">
    <div class="card ca-card">
        <header class="card-header">
            <p class="card-header-title">
                Miranda
            </p>
        </header>
        <div class="box ca-box">
            <div class="ca-message">
                <span class="tag is-info">Hey, what's up?</span>
            </div>
            <div>
                <span class="tag is-danger">Hey Dom, nothing much just chollin bruv</span>
            </div>
            <div class="ca-message">
                <span class="tag is-info">Bloooddy oath my g, hows the fam</span>
            </div>
            <div>
                <span class="tag is-danger">Bruv, the fam is on point</span>
            </div>
            <div class="ca-message">
                <span class="tag is-info">100% my g</span>
            </div>

            
        </div>
        <div class="field">
            <div class="control">
                <input class="input is-info" type="text" placeholder="write something...">
            </div>
        </div>
    </div>
</div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.card{
    background-color: white;
    min-height: 100vh;
}

.message {
    background-color:white;
}
.card-header{
    color:blue;
}

.ca-message {
  display: flex;
  justify-content: flex-end;
}

.ca-card {
    display: flex;
    flex-direction: column;
}

.ca-box {
    flex: 1;
}

</style>


