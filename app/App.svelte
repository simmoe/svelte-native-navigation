<page actionBarHidden={true}>
    <Page1 />
</page>

<script>
//first: tns plugin add @nstudio/nativescript-cardview
import { registerNativeViewElement } from 'svelte-native/dom'
registerNativeViewElement("cardView", () => require("@nstudio/nativescript-cardview").CardView);

    import Page1 from './screens/Page1.svelte'
    import Page2 from './screens/Page2.svelte'
    import Page3 from './screens/Page3.svelte'

</script>

