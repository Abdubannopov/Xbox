<template>
    <div class="">
        <div class="header">
            <div class="header-inner container mx-auto flex items-center justify-between">
                <a href="#" class="logo block">
                    <img class="logo-lg"  src="~/assets/images/svg/logo.svg" />
                    <img class="logo-sm"  src="~/assets/images/svg/small-logo.svg" />
                </a>
                <div class="header-bar flex items-center">
                    <div class="navbar">
                            <ul class="nav flex items-center">
                                <li class="nav-item">
                                    <div class="dropdown">
                                        <div class="dropdown-btn flex items-center">
                                            <span>Games</span>
                                            <img src="~/assets/images/svg/down-arrow.svg" alt="down">
                                        </div>
                                        <ul class="dropdown-list">
                                            <li class="dropdown-list-item"></li>
                                            <li class="dropdown-list-item"></li>
                                            <li class="dropdown-list-item"></li>
                                        </ul>
                                    </div>
                                </li>
                                <li class="nav-item">
                                    <div class="dropdown">
                                        <button class="dropdown-btn flex items-center">
                                            <span>Consoles</span>
                                            <img src="~/assets/images/svg/down-arrow.svg" alt="down">
                                        </button>
                                        <ul class="dropdown-list">
                                            <li class="dropdown-list-item"></li>
                                            <li class="dropdown-list-item"></li>
                                            <li class="dropdown-list-item"></li>
                                        </ul>
                                    </div>
                                </li>
                                <li class="nav-item">
                                    <button class="dropdown-btn flex">
                                            <span>Community</span>
                                        </button>
                                </li>
                            </ul>
                    </div>
                    <div class="search">
                        <input type="search" class="search-input" placeholder="Search">
                    </div>
                    <div class="navbar-mini">
                        <button class="navbar-mini-btn">
                                <img src="~/assets/images/svg/menu.svg" alt="" class="navbar-mini-btn-img" width="29" height="29">
                        </button>
                    </div>
                    <div class="profile">
                        <button class="profile-btn flex items-center">
                            <img src="~/assets/images/svg/user.svg" alt="" class="profile-btn-img">
                            <span>My XBOX</span>
                            <img src="~/assets/images/svg/down-arrow.svg" alt="" class="profile-btn-img-drop">
                        </button>
                    </div>

                </div>
            </div>
        </div>
    </div>
</template>