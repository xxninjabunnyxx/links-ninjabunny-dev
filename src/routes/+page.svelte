<script lang="ts" >
import SocialContainer from "$components/SocialContainer.svelte";
export let data: { socials: Socials }

$: ({ siteConfig } = data)
</script>

<div class="social-box">
    <SocialContainer/>
</div>