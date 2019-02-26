<template>
    <div>
        <b-navbar type="dark" variant="dark">
            <b-navbar-brand href="#">
            <img src="https://root.cern.ch/img/logos/ROOT_Logo/misc/generic-logo-white-512.png" class="d-inline-block align-top" alt="BV" style="width: 30px;"/>  DANIBELAJARVUE
            </b-navbar-brand>
            <b-navbar-toggle target="nav_collapse" />
            <b-collapse is-nav id="nav_collapse">
                <b-navbar-nav>
                <b-nav-item href="#">Profile</b-nav-item>
                <b-nav-item href="#">Discography</b-nav-item>
                <b-nav-item-dropdown text="Store">
                    <b-dropdown-item href="#">CD</b-dropdown-item>
                    <b-dropdown-item href="#">DVD</b-dropdown-item>
                    <b-dropdown-item href="#">Vinyl</b-dropdown-item>
                    <b-dropdown-item href="#">Merchandise</b-dropdown-item>
                </b-nav-item-dropdown>
                <b-nav-item-dropdown text="Schedule">
                    <b-dropdown-item href="#">TV Show</b-dropdown-item>
                    <b-dropdown-item href="#">Performance</b-dropdown-item>
                    <b-dropdown-item href="#">Concert</b-dropdown-item>
                </b-nav-item-dropdown>
                </b-navbar-nav>

                <!-- Right aligned nav items -->
                <b-navbar-nav class="ml-auto">
                    <b-nav-form>
                        <b-form-input size="sm" class="mr-sm-2" type="text" placeholder="Search" />
                        <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
                    </b-nav-form>
                    <b-nav-item-dropdown right>
                        <!-- Using button-content slot -->
                        <template slot="button-content"><em>User</em></template>
                        <b-dropdown-item href="#">Profile</b-dropdown-item>
                        <b-dropdown-item href="#">Signout</b-dropdown-item>
                    </b-nav-item-dropdown>
                </b-navbar-nav>
            </b-collapse>
        </b-navbar>
    </div>
</template>
