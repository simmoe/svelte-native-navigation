<flexboxLayout class='flex-centered'>
    <label class='h1 text-center' text='page 3' />
    <button on:tap={goToPage} text='Fullpage'/>
</flexboxLayout>


<script>
    import FullPage from '../pages/FullPage.svelte'
    import { navigate } from 'svelte-native'

    const goToPage = () => {
        console.log('navigating')
        navigate({
            page: FullPage,
        })
    }
</script>
