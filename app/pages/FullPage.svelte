<page class='bg-primary'>
    <actionBar title='Here is a full page'/>
    <flexboxLayout class='flex-centered'>
        <label textWrap={true} class='h2 text-center' text='This page is in a different navigation context' />
        <label textWrap={true} class='text-center'>
            You can either hit back in the top left corner of the device window, or import and call goBack()        
        </label>
        <button on:tap={ () => goBack() } text='go back' />
    </flexboxLayout>
</page>

<script>
    import {goBack} from 'svelte-native'
</script>
<style>
</style>