<template>
    <div>
        <h4>Search for a school in Nepal</h4>
        <input type="text" placeholder="KTM school" />

        <div class="sidebar-button-social-media">
            <b-button v-b-toggle.sidebar-1>Share us on Social Media</b-button>
            <b-sidebar id="sidebar-1" title="share sidebar" backdrop-variant="secondary" backdrop shadow="lg">
            <div class="px-3 py-2">
                <p>
                <ul>
                    <li>Facebook</li>
                    <li>Instagram</li>
                    <li>Twitter</li>
                </ul>
                </p>
                <b-img src="https://lh3.googleusercontent.com/proxy/EG_0IRIy1BqhcR2PSPZ_1usD62cDWZPb5dB3WA4jPLoxN1kGgmxbYVdtrgRgfvIBKmSGt1s3SzD3NoFz-AgGk2J8gHKssISTQF_h1s5BswyDIRCl0n_iqRowJA" fluid thumbnail></b-img>
            </div>
            </b-sidebar>
        </div>
    </div>
</template>

<style lang="scss">
    input[type="text"]{
    text-align: center;
    }

    .sidebar-button-social-media{
        margin-top: 10px;
    }
</style>
