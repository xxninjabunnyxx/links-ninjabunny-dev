<script lang="ts" >
import SocialContainer from "$components/SocialContainer.svelte";
export let data: { socials: Socials }

$: ({ siteConfig } = data)
</script>

<div class="social-box">
    <SocialContainer />
</div>

<style>
.social-box {
    display: flex;
    max-width: 26rem;
    justify-content: center;
    margin-left: auto;
    margin-right: auto;
    margin-top: 2rem;
}
</style>