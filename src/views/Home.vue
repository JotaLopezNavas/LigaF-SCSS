<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-12">
          <div id="bodycontent">
              <div id="upcoming">
                <h2>August 4</h2>
                <p class="indent">NYSL Fundraiser</p>

                <h2>August 16</h2>
                <p class="indent">Season Kick-off: Meet the Teams</p>
                
                <h2>September 1</h2>
                <p class="indent"> First Game of the Season (Check Game Schedule for details)</p>
              </div>
            </div>
         </div>
    </div>
    <!-- <div class="row">
       <div class="col-12"> -->
          <Piso/>
       <!-- </div>
    </div> -->
 
  </div>

</template>

<script>
import Piso from '@/components/piso.vue'

// @ is an alias to /src



export default {
  name: 'Home',
  components: {
    Piso
  }
}
</script>
