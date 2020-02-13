<template>
    <div>
        <pre style="color:#ff0000">{{ message }}</pre>
        <div class="ui tabular menu tabs">
            <div class="item active" data-tab="tab1c">Tab1</div>
            <div class="item" data-tab="tab2c">Tab2</div>
        </div> 
        <div class="ui tab active" data-tab="tab1c">After the laws of physics, everything else is opinion.</div>
        <div class="ui tab" data-tab="tab2c">Black holes are where God divided by zero.</div>   
    </div> 
</template>

<script>
export default {
   props: ['message'],
};
</script>