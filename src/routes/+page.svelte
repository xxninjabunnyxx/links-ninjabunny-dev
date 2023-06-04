<script lang="ts" >
export let data: { socials: Socials }

$: ({ socials } = data)
</script>


<header>NinjaBunny</header>

<div class="social-box">
    {#each socials as social}
        <div class="social"></div>
    {/each}
</div>