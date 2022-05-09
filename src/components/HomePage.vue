<script>
export default {
  data() {
    return {
      sideBar: {
        Home: {
          iconActive:
            '<svg viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-lwhw9o r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><path d="M22.58 7.35L12.475 1.897c-.297-.16-.654-.16-.95 0L1.425 7.35c-.486.264-.667.87-.405 1.356.18.335.525.525.88.525.16 0 .324-.038.475-.12l.734-.396 1.59 11.25c.216 1.214 1.31 2.062 2.66 2.062h9.282c1.35 0 2.444-.848 2.662-2.088l1.588-11.225.737.398c.485.263 1.092.082 1.354-.404.263-.486.08-1.093-.404-1.355zM12 15.435c-1.795 0-3.25-1.455-3.25-3.25s1.455-3.25 3.25-3.25 3.25 1.455 3.25 3.25-1.455 3.25-3.25 3.25z"></path></g></svg>',
          icon: '<svg viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-lwhw9o r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><path d="M22.46 7.57L12.357 2.115c-.223-.12-.49-.12-.713 0L1.543 7.57c-.364.197-.5.652-.303 1.017.135.25.394.393.66.393.12 0 .243-.03.356-.09l.815-.44L4.7 19.963c.214 1.215 1.308 2.062 2.658 2.062h9.282c1.352 0 2.445-.848 2.663-2.087l1.626-11.49.818.442c.364.193.82.06 1.017-.304.196-.363.06-.818-.304-1.016zm-4.638 12.133c-.107.606-.703.822-1.18.822H7.36c-.48 0-1.075-.216-1.178-.798L4.48 7.69 12 3.628l7.522 4.06-1.7 12.015z"></path><path d="M8.22 12.184c0 2.084 1.695 3.78 3.78 3.78s3.78-1.696 3.78-3.78-1.695-3.78-3.78-3.78-3.78 1.696-3.78 3.78zm6.06 0c0 1.258-1.022 2.28-2.28 2.28s-2.28-1.022-2.28-2.28 1.022-2.28 2.28-2.28 2.28 1.022 2.28 2.28z"></path></g></svg>',
          name: "Home",
        },
        Explore: {
          iconActive:
            '<svg viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-lwhw9o r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><path d="M20.585 9.468c.66 0 1.2-.538 1.2-1.2 0-.662-.54-1.2-1.2-1.2h-3.22l.31-3.547c.027-.318-.07-.63-.277-.875-.206-.245-.495-.396-.822-.425-.65-.035-1.235.432-1.293 1.093l-.326 3.754H9.9l.308-3.545c.06-.658-.43-1.242-1.097-1.302-.665-.05-1.235.43-1.293 1.092l-.325 3.754h-3.33c-.663 0-1.2.538-1.2 1.2 0 .662.538 1.2 1.2 1.2h3.122l-.44 5.064H3.416c-.662 0-1.2.54-1.2 1.2s.538 1.202 1.2 1.202h3.22l-.31 3.548c-.057.657.432 1.24 1.09 1.3l.106.005c.626 0 1.14-.472 1.195-1.098l.327-3.753H14.1l-.308 3.544c-.06.658.43 1.242 1.09 1.302l.106.005c.617 0 1.142-.482 1.195-1.098l.325-3.753h3.33c.66 0 1.2-.54 1.2-1.2s-.54-1.202-1.2-1.202h-3.122l.44-5.064h3.43zm-5.838 0l-.44 5.063H9.253l.44-5.062h5.055z"></path></g></svg>',
          icon: '<svg viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-lwhw9o r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><path d="M21.53 20.47l-3.66-3.66C19.195 15.24 20 13.214 20 11c0-4.97-4.03-9-9-9s-9 4.03-9 9 4.03 9 9 9c2.215 0 4.24-.804 5.808-2.13l3.66 3.66c.147.146.34.22.53.22s.385-.073.53-.22c.295-.293.295-.767.002-1.06zM3.5 11c0-4.135 3.365-7.5 7.5-7.5s7.5 3.365 7.5 7.5-3.365 7.5-7.5 7.5-7.5-3.365-7.5-7.5z"></path></g></svg>',
          name: "Explore",
        },
        Notifications: {
          iconActive:
            '<svg viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-lwhw9o r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><path d="M21.697 16.468c-.02-.016-2.14-1.64-2.103-6.03.02-2.533-.812-4.782-2.347-6.334-1.375-1.393-3.237-2.164-5.242-2.172h-.013c-2.004.008-3.866.78-5.242 2.172-1.534 1.553-2.367 3.802-2.346 6.333.037 4.332-2.02 5.967-2.102 6.03-.26.194-.366.53-.265.838s.39.515.713.515h4.494c.1 2.544 2.188 4.587 4.756 4.587s4.655-2.043 4.756-4.587h4.494c.324 0 .61-.208.712-.515s-.005-.644-.265-.837zM12 20.408c-1.466 0-2.657-1.147-2.756-2.588h5.512c-.1 1.44-1.29 2.587-2.756 2.587z"></path></g></svg>',
          icon: '<svg viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-lwhw9o r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><path d="M21.697 16.468c-.02-.016-2.14-1.64-2.103-6.03.02-2.532-.812-4.782-2.347-6.335C15.872 2.71 14.01 1.94 12.005 1.93h-.013c-2.004.01-3.866.78-5.242 2.174-1.534 1.553-2.368 3.802-2.346 6.334.037 4.33-2.02 5.967-2.102 6.03-.26.193-.366.53-.265.838.102.308.39.515.712.515h4.92c.102 2.31 1.997 4.16 4.33 4.16s4.226-1.85 4.327-4.16h4.922c.322 0 .61-.206.71-.514.103-.307-.003-.645-.263-.838zM12 20.478c-1.505 0-2.73-1.177-2.828-2.658h5.656c-.1 1.48-1.323 2.66-2.828 2.66zM4.38 16.32c.74-1.132 1.548-3.028 1.524-5.896-.018-2.16.644-3.982 1.913-5.267C8.91 4.05 10.397 3.437 12 3.43c1.603.008 3.087.62 4.18 1.728 1.27 1.285 1.933 3.106 1.915 5.267-.024 2.868.785 4.765 1.525 5.896H4.38z"></path></g></svg>',
          name: "Notifications",
        },
        Messages: {
          iconActive:
            '<svg viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-lwhw9o r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><path d="M11.55 12.082c.273.182.627.182.9 0L22 5.716V5.5c0-1.24-1.01-2.25-2.25-2.25H4.25C3.01 3.25 2 4.26 2 5.5v.197l9.55 6.385z"></path><path d="M13.26 13.295c-.383.255-.82.382-1.26.382s-.877-.127-1.26-.383L2 7.452v11.67c0 1.24 1.01 2.25 2.25 2.25h15.5c1.24 0 2.25-1.01 2.25-2.25V7.47l-8.74 5.823z"></path></g></svg>',
          icon: '<svg viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-lwhw9o r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><path d="M19.25 3.018H4.75C3.233 3.018 2 4.252 2 5.77v12.495c0 1.518 1.233 2.753 2.75 2.753h14.5c1.517 0 2.75-1.235 2.75-2.753V5.77c0-1.518-1.233-2.752-2.75-2.752zm-14.5 1.5h14.5c.69 0 1.25.56 1.25 1.25v.714l-8.05 5.367c-.273.18-.626.182-.9-.002L3.5 6.482v-.714c0-.69.56-1.25 1.25-1.25zm14.5 14.998H4.75c-.69 0-1.25-.56-1.25-1.25V8.24l7.24 4.83c.383.256.822.384 1.26.384.44 0 .877-.128 1.26-.383l7.24-4.83v10.022c0 .69-.56 1.25-1.25 1.25z"></path></g></svg>',
          name: "Messages",
        },
        Bookmarks: {
          iconActive:
            '<svg viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-lwhw9o r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><path d="M19.9 23.5c-.2 0-.3 0-.4-.1L12 17.9l-7.5 5.4c-.2.2-.5.2-.8.1-.2-.1-.4-.4-.4-.7V5.6c0-1.2 1-2.2 2.2-2.2h12.8c1.2 0 2.2 1 2.2 2.2v17.1c0 .3-.2.5-.4.7 0 .1-.1.1-.2.1z"></path></g></svg>',
          icon: '<svg viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-lwhw9o r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><path d="M19.9 23.5c-.157 0-.312-.05-.442-.144L12 17.928l-7.458 5.43c-.228.164-.53.19-.782.06-.25-.127-.41-.385-.41-.667V5.6c0-1.24 1.01-2.25 2.25-2.25h12.798c1.24 0 2.25 1.01 2.25 2.25v17.15c0 .282-.158.54-.41.668-.106.055-.223.082-.34.082zM12 16.25c.155 0 .31.048.44.144l6.71 4.883V5.6c0-.412-.337-.75-.75-.75H5.6c-.413 0-.75.338-.75.75v15.677l6.71-4.883c.13-.096.285-.144.44-.144z"></path></g></svg>',
          name: "Bookmarks",
        },
        Lists: {
          iconActive:
            '<svg viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-lwhw9o r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><path d="M19.75 2H4.25C3.013 2 2 3.013 2 4.25v15.5C2 20.987 3.013 22 4.25 22h15.5c1.237 0 2.25-1.013 2.25-2.25V4.25C22 3.013 20.987 2 19.75 2zM11 16.75H7c-.414 0-.75-.336-.75-.75s.336-.75.75-.75h4c.414 0 .75.336.75.75s-.336.75-.75.75zm6-4H7c-.414 0-.75-.336-.75-.75s.336-.75.75-.75h10c.414 0 .75.336.75.75s-.336.75-.75.75zm0-4H7c-.414 0-.75-.336-.75-.75s.336-.75.75-.75h10c.414 0 .75.336.75.75s-.336.75-.75.75z"></path></g></svg>',
          icon: '<svg viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-lwhw9o r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><path d="M19.75 22H4.25C3.01 22 2 20.99 2 19.75V4.25C2 3.01 3.01 2 4.25 2h15.5C20.99 2 22 3.01 22 4.25v15.5c0 1.24-1.01 2.25-2.25 2.25zM4.25 3.5c-.414 0-.75.337-.75.75v15.5c0 .413.336.75.75.75h15.5c.414 0 .75-.337.75-.75V4.25c0-.413-.336-.75-.75-.75H4.25z"></path><path d="M17 8.64H7c-.414 0-.75-.337-.75-.75s.336-.75.75-.75h10c.414 0 .75.335.75.75s-.336.75-.75.75zm0 4.11H7c-.414 0-.75-.336-.75-.75s.336-.75.75-.75h10c.414 0 .75.336.75.75s-.336.75-.75.75zm-5 4.11H7c-.414 0-.75-.335-.75-.75s.336-.75.75-.75h5c.414 0 .75.337.75.75s-.336.75-.75.75z"></path></g></svg>',
          name: "Lists",
        },
        Profile: {
          iconActive:
            '<svg viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-lwhw9o r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><path d="M12.225 12.165c-1.356 0-2.872-.15-3.84-1.256-.814-.93-1.077-2.368-.805-4.392.38-2.826 2.116-4.513 4.646-4.513s4.267 1.687 4.646 4.513c.272 2.024.008 3.46-.806 4.392-.97 1.106-2.485 1.255-3.84 1.255zm5.849 9.85H6.376c-.663 0-1.25-.28-1.65-.786-.422-.534-.576-1.27-.41-1.968.834-3.53 4.086-5.997 7.908-5.997s7.074 2.466 7.91 5.997c.164.698.01 1.434-.412 1.967-.4.505-.985.785-1.648.785z"></path></g></svg>',
          icon: '<svg viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-lwhw9o r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><path d="M12 11.816c1.355 0 2.872-.15 3.84-1.256.814-.93 1.078-2.368.806-4.392-.38-2.825-2.117-4.512-4.646-4.512S7.734 3.343 7.354 6.17c-.272 2.022-.008 3.46.806 4.39.968 1.107 2.485 1.256 3.84 1.256zM8.84 6.368c.162-1.2.787-3.212 3.16-3.212s2.998 2.013 3.16 3.212c.207 1.55.057 2.627-.45 3.205-.455.52-1.266.743-2.71.743s-2.255-.223-2.71-.743c-.507-.578-.657-1.656-.45-3.205zm11.44 12.868c-.877-3.526-4.282-5.99-8.28-5.99s-7.403 2.464-8.28 5.99c-.172.692-.028 1.4.395 1.94.408.52 1.04.82 1.733.82h12.304c.693 0 1.325-.3 1.733-.82.424-.54.567-1.247.394-1.94zm-1.576 1.016c-.126.16-.316.246-.552.246H5.848c-.235 0-.426-.085-.552-.246-.137-.174-.18-.412-.12-.654.71-2.855 3.517-4.85 6.824-4.85s6.114 1.994 6.824 4.85c.06.242.017.48-.12.654z"></path></g></svg>',
          name: "Profile",
        },
      },
      more: {
        icon: '<svg viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-lwhw9o r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><circle cx="17" cy="12" r="1.5"></circle><circle cx="12" cy="12" r="1.5"></circle><circle cx="7" cy="12" r="1.5"></circle><path d="M12 22.75C6.072 22.75 1.25 17.928 1.25 12S6.072 1.25 12 1.25 22.75 6.072 22.75 12 17.928 22.75 12 22.75zm0-20C6.9 2.75 2.75 6.9 2.75 12S6.9 21.25 12 21.25s9.25-4.15 9.25-9.25S17.1 2.75 12 2.75z"></path></g></svg>',
        name: "More",
      },
      threeDots:
        '<svg class="fill-gray-500 hover:fill-blue-500" viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-1xvli5t r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><circle cx="5" cy="12" r="2"></circle><circle cx="12" cy="12" r="2"></circle><circle cx="19" cy="12" r="2"></circle></g></svg>',
      trending: {
        1: {
          trend: "#FareWellKibaki",
          number: "9,343",
        },
        2: {
          trend: "#OmokaNaGabriel1XBet",
          number: "3,366",
        },
        3: {
          trend: "#MasculinitySaturday",
          number: "8,867",
        },
        4: {
          trend: "NewCastle",
          number: "9,343",
        },
        5: {
          trend: "#Othaya",
          number: "12.1K",
        },
        6: {
          trend: "#Liverpool",
          number: "70.5K",
        },
        7: {
          trend: "#KIPRONOH",
          number: "2,343",
        },
        8: {
          trend: "#Nyayo Stadium",
          number: "12.5K",
        },
        9: {
          trend: "#Munch",
          number: "9,179",
        },
        10: {
          trend: "#Bishop Muheria",
          number: "6,523",
        },
      },
      textAreaIcons: {
        media:
          '<svg class="fill-sky-500"  viewBox="0 0 24 24" aria-hidden="true" class="r-1cvl2hr r-4qtqp9 r-yyyyoo r-z80fyv r-dnmrzs r-bnwqim r-1plcrui r-lrvibr r-19wmn03"><g><path d="M19.75 2H4.25C3.01 2 2 3.01 2 4.25v15.5C2 20.99 3.01 22 4.25 22h15.5c1.24 0 2.25-1.01 2.25-2.25V4.25C22 3.01 20.99 2 19.75 2zM4.25 3.5h15.5c.413 0 .75.337.75.75v9.676l-3.858-3.858c-.14-.14-.33-.22-.53-.22h-.003c-.2 0-.393.08-.532.224l-4.317 4.384-1.813-1.806c-.14-.14-.33-.22-.53-.22-.193-.03-.395.08-.535.227L3.5 17.642V4.25c0-.413.337-.75.75-.75zm-.744 16.28l5.418-5.534 6.282 6.254H4.25c-.402 0-.727-.322-.744-.72zm16.244.72h-2.42l-5.007-4.987 3.792-3.85 4.385 4.384v3.703c0 .413-.337.75-.75.75z"></path><circle cx="8.868" cy="8.309" r="1.542"></circle></g></svg>',
        gif: '<svg class="fill-sky-500" viewBox="0 0 24 24" aria-hidden="true" class="r-1cvl2hr r-4qtqp9 r-yyyyoo r-z80fyv r-dnmrzs r-bnwqim r-1plcrui r-lrvibr r-19wmn03"><g><path d="M19 10.5V8.8h-4.4v6.4h1.7v-2h2v-1.7h-2v-1H19zm-7.3-1.7h1.7v6.4h-1.7V8.8zm-3.6 1.6c.4 0 .9.2 1.2.5l1.2-1C9.9 9.2 9 8.8 8.1 8.8c-1.8 0-3.2 1.4-3.2 3.2s1.4 3.2 3.2 3.2c1 0 1.8-.4 2.4-1.1v-2.5H7.7v1.2h1.2v.6c-.2.1-.5.2-.8.2-.9 0-1.6-.7-1.6-1.6 0-.8.7-1.6 1.6-1.6z"></path><path d="M20.5 2.02h-17c-1.24 0-2.25 1.007-2.25 2.247v15.507c0 1.238 1.01 2.246 2.25 2.246h17c1.24 0 2.25-1.008 2.25-2.246V4.267c0-1.24-1.01-2.247-2.25-2.247zm.75 17.754c0 .41-.336.746-.75.746h-17c-.414 0-.75-.336-.75-.746V4.267c0-.412.336-.747.75-.747h17c.414 0 .75.335.75.747v15.507z"></path></g></svg>',
        poll: '<svg class="fill-sky-500" viewBox="0 0 24 24" aria-hidden="true" class="r-1cvl2hr r-4qtqp9 r-yyyyoo r-z80fyv r-dnmrzs r-bnwqim r-1plcrui r-lrvibr r-19wmn03"><g><path d="M20.222 9.16h-1.334c.015-.09.028-.182.028-.277V6.57c0-.98-.797-1.777-1.778-1.777H3.5V3.358c0-.414-.336-.75-.75-.75s-.75.336-.75.75V20.83c0 .415.336.75.75.75s.75-.335.75-.75v-1.434h10.556c.98 0 1.778-.797 1.778-1.777v-2.313c0-.095-.014-.187-.028-.278h4.417c.98 0 1.778-.798 1.778-1.778v-2.31c0-.983-.797-1.78-1.778-1.78zM17.14 6.293c.152 0 .277.124.277.277v2.31c0 .154-.125.28-.278.28H3.5V6.29h13.64zm-2.807 9.014v2.312c0 .153-.125.277-.278.277H3.5v-2.868h10.556c.153 0 .277.126.277.28zM20.5 13.25c0 .153-.125.277-.278.277H3.5V10.66h16.722c.153 0 .278.124.278.277v2.313z"></path></g></svg>',
        emoji:
          '<svg class="fill-sky-500" viewBox="0 0 24 24" aria-hidden="true" class="r-1cvl2hr r-4qtqp9 r-yyyyoo r-z80fyv r-dnmrzs r-bnwqim r-1plcrui r-lrvibr r-19wmn03"><g><path d="M12 22.75C6.072 22.75 1.25 17.928 1.25 12S6.072 1.25 12 1.25 22.75 6.072 22.75 12 17.928 22.75 12 22.75zm0-20C6.9 2.75 2.75 6.9 2.75 12S6.9 21.25 12 21.25s9.25-4.15 9.25-9.25S17.1 2.75 12 2.75z"></path><path d="M12 17.115c-1.892 0-3.633-.95-4.656-2.544-.224-.348-.123-.81.226-1.035.348-.226.812-.124 1.036.226.747 1.162 2.016 1.855 3.395 1.855s2.648-.693 3.396-1.854c.224-.35.688-.45 1.036-.225.35.224.45.688.226 1.036-1.025 1.594-2.766 2.545-4.658 2.545z"></path><circle cx="14.738" cy="9.458" r="1.478"></circle><circle cx="9.262" cy="9.458" r="1.478"></circle></g></svg>',
        schedule:
          '<svg class="fill-sky-500" viewBox="0 0 24 24" aria-hidden="true" class="r-1cvl2hr r-4qtqp9 r-yyyyoo r-z80fyv r-dnmrzs r-bnwqim r-1plcrui r-lrvibr r-19wmn03"><g><path d="M-37.9 18c-.1-.1-.1-.1-.1-.2.1 0 .1.1.1.2z"></path><path d="M-37.9 18c-.1-.1-.1-.1-.1-.2.1 0 .1.1.1.2zM18 2.2h-1.3v-.3c0-.4-.3-.8-.8-.8-.4 0-.8.3-.8.8v.3H7.7v-.3c0-.4-.3-.8-.8-.8-.4 0-.8.3-.8.8v.3H4.8c-1.4 0-2.5 1.1-2.5 2.5v13.1c0 1.4 1.1 2.5 2.5 2.5h2.9c.4 0 .8-.3.8-.8 0-.4-.3-.8-.8-.8H4.8c-.6 0-1-.5-1-1V7.9c0-.3.4-.7 1-.7H18c.6 0 1 .4 1 .7v1.8c0 .4.3.8.8.8.4 0 .8-.3.8-.8v-5c-.1-1.4-1.2-2.5-2.6-2.5zm1 3.7c-.3-.1-.7-.2-1-.2H4.8c-.4 0-.7.1-1 .2V4.7c0-.6.5-1 1-1h1.3v.5c0 .4.3.8.8.8.4 0 .8-.3.8-.8v-.5h7.5v.5c0 .4.3.8.8.8.4 0 .8-.3.8-.8v-.5H18c.6 0 1 .5 1 1v1.2z"></path><path d="M15.5 10.4c-3.4 0-6.2 2.8-6.2 6.2 0 3.4 2.8 6.2 6.2 6.2 3.4 0 6.2-2.8 6.2-6.2 0-3.4-2.8-6.2-6.2-6.2zm0 11c-2.6 0-4.7-2.1-4.7-4.7s2.1-4.7 4.7-4.7 4.7 2.1 4.7 4.7c0 2.5-2.1 4.7-4.7 4.7z"></path><path d="M18.9 18.7c-.1.2-.4.4-.6.4-.1 0-.3 0-.4-.1l-3.1-2v-3c0-.4.3-.8.8-.8.4 0 .8.3.8.8v2.2l2.4 1.5c.2.2.3.6.1 1z"></path></g></svg>',
        location:
          '<svg class="fill-sky-500" viewBox="0 0 24 24" aria-hidden="true" class="r-1cvl2hr r-4qtqp9 r-yyyyoo r-z80fyv r-dnmrzs r-bnwqim r-1plcrui r-lrvibr r-19wmn03"><g><path d="M12 14.315c-2.088 0-3.787-1.698-3.787-3.786S9.913 6.74 12 6.74s3.787 1.7 3.787 3.787-1.7 3.785-3.787 3.785zm0-6.073c-1.26 0-2.287 1.026-2.287 2.287S10.74 12.814 12 12.814s2.287-1.025 2.287-2.286S13.26 8.24 12 8.24z"></path><path d="M20.692 10.69C20.692 5.9 16.792 2 12 2s-8.692 3.9-8.692 8.69c0 1.902.603 3.708 1.743 5.223l.003-.002.007.015c1.628 2.07 6.278 5.757 6.475 5.912.138.11.302.163.465.163.163 0 .327-.053.465-.162.197-.155 4.847-3.84 6.475-5.912l.007-.014.002.002c1.14-1.516 1.742-3.32 1.742-5.223zM12 20.29c-1.224-.99-4.52-3.715-5.756-5.285-.94-1.25-1.436-2.742-1.436-4.312C4.808 6.727 8.035 3.5 12 3.5s7.192 3.226 7.192 7.19c0 1.57-.497 3.062-1.436 4.313-1.236 1.57-4.532 4.294-5.756 5.285z"></path></g></svg>',
      },
      tweetIcons: {
        comment:
          '<svg class="fill-gray-500 group-hover:fill-blue-500" viewBox="0 0 24 24" aria-hidden="true" class="r-4qtqp9 r-yyyyoo r-1xvli5t r-dnmrzs r-bnwqim r-1plcrui r-lrvibr r-1hdv0qi"><g><path d="M14.046 2.242l-4.148-.01h-.002c-4.374 0-7.8 3.427-7.8 7.802 0 4.098 3.186 7.206 7.465 7.37v3.828c0 .108.044.286.12.403.142.225.384.347.632.347.138 0 .277-.038.402-.118.264-.168 6.473-4.14 8.088-5.506 1.902-1.61 3.04-3.97 3.043-6.312v-.017c-.006-4.367-3.43-7.787-7.8-7.788zm3.787 12.972c-1.134.96-4.862 3.405-6.772 4.643V16.67c0-.414-.335-.75-.75-.75h-.396c-3.66 0-6.318-2.476-6.318-5.886 0-3.534 2.768-6.302 6.3-6.302l4.147.01h.002c3.532 0 6.3 2.766 6.302 6.296-.003 1.91-.942 3.844-2.514 5.176z"></path></g></svg>',
        retweet:
          '<svg class="fill-gray-500 group-hover:fill-green-500" viewBox="0 0 24 24" aria-hidden="true" class="r-4qtqp9 r-yyyyoo r-1xvli5t r-dnmrzs r-bnwqim r-1plcrui r-lrvibr r-1hdv0qi"><g><path d="M23.77 15.67c-.292-.293-.767-.293-1.06 0l-2.22 2.22V7.65c0-2.068-1.683-3.75-3.75-3.75h-5.85c-.414 0-.75.336-.75.75s.336.75.75.75h5.85c1.24 0 2.25 1.01 2.25 2.25v10.24l-2.22-2.22c-.293-.293-.768-.293-1.06 0s-.294.768 0 1.06l3.5 3.5c.145.147.337.22.53.22s.383-.072.53-.22l3.5-3.5c.294-.292.294-.767 0-1.06zm-10.66 3.28H7.26c-1.24 0-2.25-1.01-2.25-2.25V6.46l2.22 2.22c.148.147.34.22.532.22s.384-.073.53-.22c.293-.293.293-.768 0-1.06l-3.5-3.5c-.293-.294-.768-.294-1.06 0l-3.5 3.5c-.294.292-.294.767 0 1.06s.767.293 1.06 0l2.22-2.22V16.7c0 2.068 1.683 3.75 3.75 3.75h5.85c.414 0 .75-.336.75-.75s-.337-.75-.75-.75z"></path></g></svg>',
        like: '<svg class="fill-gray-500 group-hover:fill-pink-500" viewBox="0 0 24 24" aria-hidden="true" class="r-4qtqp9 r-yyyyoo r-1xvli5t r-dnmrzs r-bnwqim r-1plcrui r-lrvibr r-1hdv0qi"><g><path d="M12 21.638h-.014C9.403 21.59 1.95 14.856 1.95 8.478c0-3.064 2.525-5.754 5.403-5.754 2.29 0 3.83 1.58 4.646 2.73.814-1.148 2.354-2.73 4.645-2.73 2.88 0 5.404 2.69 5.404 5.755 0 6.376-7.454 13.11-10.037 13.157H12zM7.354 4.225c-2.08 0-3.903 1.988-3.903 4.255 0 5.74 7.034 11.596 8.55 11.658 1.518-.062 8.55-5.917 8.55-11.658 0-2.267-1.823-4.255-3.903-4.255-2.528 0-3.94 2.936-3.952 2.965-.23.562-1.156.562-1.387 0-.014-.03-1.425-2.965-3.954-2.965z"></path></g></svg>',
        share:
          '<svg class="fill-gray-500 group-hover:fill-blue-500" viewBox="0 0 24 24" aria-hidden="true" class="r-4qtqp9 r-yyyyoo r-1xvli5t r-dnmrzs r-bnwqim r-1plcrui r-lrvibr r-1hdv0qi"><g><path d="M17.53 7.47l-5-5c-.293-.293-.768-.293-1.06 0l-5 5c-.294.293-.294.768 0 1.06s.767.294 1.06 0l3.72-3.72V15c0 .414.336.75.75.75s.75-.336.75-.75V4.81l3.72 3.72c.146.147.338.22.53.22s.384-.072.53-.22c.293-.293.293-.767 0-1.06z"></path><path d="M19.708 21.944H4.292C3.028 21.944 2 20.916 2 19.652V14c0-.414.336-.75.75-.75s.75.336.75.75v5.652c0 .437.355.792.792.792h15.416c.437 0 .792-.355.792-.792V14c0-.414.336-.75.75-.75s.75.336.75.75v5.652c0 1.264-1.028 2.292-2.292 2.292z"></path></g></svg>',
      },
      verifiedIcon:
        '<svg class="fill-blue-500" class="fill-sky-500" viewBox="0 0 24 24" aria-label="Verified account" class="r-1cvl2hr r-4qtqp9 r-yyyyoo r-1xvli5t r-9cviqr r-f9ja8p r-og9te1 r-bnwqim r-1plcrui r-lrvibr"><g><path d="M22.5 12.5c0-1.58-.875-2.95-2.148-3.6.154-.435.238-.905.238-1.4 0-2.21-1.71-3.998-3.818-3.998-.47 0-.92.084-1.336.25C14.818 2.415 13.51 1.5 12 1.5s-2.816.917-3.437 2.25c-.415-.165-.866-.25-1.336-.25-2.11 0-3.818 1.79-3.818 4 0 .494.083.964.237 1.4-1.272.65-2.147 2.018-2.147 3.6 0 1.495.782 2.798 1.942 3.486-.02.17-.032.34-.032.514 0 2.21 1.708 4 3.818 4 .47 0 .92-.086 1.335-.25.62 1.334 1.926 2.25 3.437 2.25 1.512 0 2.818-.916 3.437-2.25.415.163.865.248 1.336.248 2.11 0 3.818-1.79 3.818-4 0-.174-.012-.344-.033-.513 1.158-.687 1.943-1.99 1.943-3.484zm-6.616-3.334l-4.334 6.5c-.145.217-.382.334-.625.334-.143 0-.288-.04-.416-.126l-.115-.094-2.415-2.415c-.293-.293-.293-.768 0-1.06s.768-.294 1.06 0l1.77 1.767 3.825-5.74c.23-.345.696-.436 1.04-.207.346.23.44.696.21 1.04z"></path></g></svg>',
      chatIcon:
        '<svg class="fill-gray-500" viewBox="0 0 24 24" aria-hidden="true" class="r-14j79pv r-4qtqp9 r-yyyyoo r-10ptun7 r-dnmrzs r-bnwqim r-1plcrui r-lrvibr r-1janqcz"><g><path d="M18.265 3.314c-3.45-3.45-9.07-3.45-12.52 0-3.45 3.44-3.45 9.06 0 12.51 1.5 1.49 3.43 2.38 5.51 2.56v4.14c0 .31.2.6.5.7.08.03.17.05.25.05.22 0 .44-.1.59-.29l6.49-8.11c2.63-3.49 2.27-8.47-.82-11.56zm-10.56 7.87c0-.41.33-.75.75-.75h4.05c.41 0 .75.34.75.75s-.34.75-.75.75h-4.05c-.42 0-.75-.34-.75-.75zm8.6-3.24c0 .42-.34.75-.75.75h-7.1c-.42 0-.75-.33-.75-.75 0-.41.33-.75.75-.75h7.1c.41 0 .75.34.75.75z"></path></g></svg>',
      tweetImage: "/src/assets/lady1.jpg",
      tweetImageWidth: undefined,
      promotedIcon:
        '<svg class="fill-gray-500" viewBox="0 0 24 24" aria-hidden="true" class="r-14j79pv r-4qtqp9 r-yyyyoo r-1q142lx r-ip8ujx r-1d4mawv r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><path d="M20.75 2H3.25C2.007 2 1 3.007 1 4.25v15.5C1 20.993 2.007 22 3.25 22h17.5c1.243 0 2.25-1.007 2.25-2.25V4.25C23 3.007 21.993 2 20.75 2zM17.5 13.504c0 .483-.392.875-.875.875s-.875-.393-.875-.876V9.967l-7.547 7.546c-.17.17-.395.256-.62.256s-.447-.086-.618-.257c-.342-.342-.342-.896 0-1.237l7.547-7.547h-3.54c-.482 0-.874-.393-.874-.876s.392-.875.875-.875h5.65c.483 0 .875.39.875.874v5.65z"></path></g></svg>',
      navStar:
        '<svg viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-z80fyv r-dnmrzs r-bnwqim r-1plcrui r-lrvibr r-19wmn03"><g><path d="M22.772 10.506l-5.618-2.192-2.16-6.5c-.102-.307-.39-.514-.712-.514s-.61.207-.712.513l-2.16 6.5-5.62 2.192c-.287.112-.477.39-.477.7s.19.585.478.698l5.62 2.192 2.16 6.5c.102.306.39.513.712.513s.61-.207.712-.513l2.16-6.5 5.62-2.192c.287-.112.477-.39.477-.7s-.19-.585-.478-.697zm-6.49 2.32c-.208.08-.37.25-.44.46l-1.56 4.695-1.56-4.693c-.07-.21-.23-.38-.438-.462l-4.155-1.62 4.154-1.622c.208-.08.37-.25.44-.462l1.56-4.693 1.56 4.694c.07.212.23.382.438.463l4.155 1.62-4.155 1.622zM6.663 3.812h-1.88V2.05c0-.414-.337-.75-.75-.75s-.75.336-.75.75v1.762H1.5c-.414 0-.75.336-.75.75s.336.75.75.75h1.782v1.762c0 .414.336.75.75.75s.75-.336.75-.75V5.312h1.88c.415 0 .75-.336.75-.75s-.335-.75-.75-.75zm2.535 15.622h-1.1v-1.016c0-.414-.335-.75-.75-.75s-.75.336-.75.75v1.016H5.57c-.414 0-.75.336-.75.75s.336.75.75.75H6.6v1.016c0 .414.335.75.75.75s.75-.336.75-.75v-1.016h1.098c.414 0 .75-.336.75-.75s-.336-.75-.75-.75z"></path></g></svg>',
      tweets: {
        tweet1: {
          userName: "Eric",
          handle: "@amerix . May 5, 2022",
          profilePicture: "amerix.jpg",
          imagewithLink: false,
          image: false,
          content:
            "Running an NGO especially an upcoming one is so strenuous and burdensome. I tried it and failed three times.However I am not giving up anytime soon.You don't need money, you need to grow thick skin and metal brains.Here is what I have learnt so far. Thread...",
          comment: "557",
          re
          
          s: "4,245",
          likes: "20.6K",
          thread: true,
          promoted: true,
          tweetImageLinked: false,
          tweetImage: "/assets/amerixbs.jpg",
          topic: "Men's Health",
          verified: true,
        },
        tweet2: {
          userName: "Elon Musk",
          handle: "@elonmusk . 23h",
          profilePicture: "/src/assets/elon.jpg",
          imagewithLink: false,
          image: false,
          content:
            "Interesting. I wonder if those funding these organizations are fully aware of what the organizations are doing.",
          comment: "557",
          retweets: "4,245",
          likes: "20.6K",
          thread: false,
          promoted: false,
          tweetImageLinked: false,
          tweetImage: "/src/assets/elonwonder.jpg",
          topic: "Technology",
          verified: true,
        },
        tweet3: {
          userName: "Andrew Kibe",
          handle: "@kibeandy . Apr 21",
          profilePicture: "/src/assets/kibe.jpg",
          imagewithLink: false,
          image: false,
          content:
            "Running an NGO especially an upcoming one is so strenuous and burdensome. I tried it and failed three times.However I am not giving up anytime soon.You don't need money, you need to grow thick skin and metal brains.Here is what I have learnt so far. Thread...",
          comment: "22",
          retweets: "28",
          likes: "150",
          thread: false,
          promoted: true,
          tweetImageLinked: false,
          tweetImage: "/src/assets/kibethoughts.jpg",
          topic: "Men's Health",
          verified: true,
        },
        tweet4: {
          userName: "Elon Musk",
          handle: "@elonmusk . 23h",
          profilePicture: "/src/assets/elon.jpg",
          imagewithLink: false,
          image: false,
          content:
            "Interesting. I wonder if those funding these organizations are fully aware of what the organizations are doing.",
          comment: "557",
          retweets: "4,245",
          likes: "20.6K",
          thread: false,
          promoted: false,
          tweetImageLinked: false,
          tweetImage: "/src/assets/elontwitter.jpg",
          topic: "Technology",
          verified: true,
          siteUrl: "cnn.com",
          siteHeading:
            "Brands should force Twitter to uphold content policies under Musk...",
          siteData:
            "Some of the nation's biggest brands including Coca-Cola, Disney and Kraft are facing calls..",
        },
      },
      mobileTweet:
        '<svg  class="fill-white" viewBox="0 0 24 24" aria-hidden="true" class="r-jwli3a r-4qtqp9 r-yyyyoo r-1472mwg r-dnmrzs r-bnwqim r-1plcrui r-lrvibr r-lrsllp"><g><path d="M8.8 7.2H5.6V3.9c0-.4-.3-.8-.8-.8s-.7.4-.7.8v3.3H.8c-.4 0-.8.3-.8.8s.3.8.8.8h3.3v3.3c0 .4.3.8.8.8s.8-.3.8-.8V8.7H9c.4 0 .8-.3.8-.8s-.5-.7-1-.7zm15-4.9v-.1h-.1c-.1 0-9.2 1.2-14.4 11.7-3.8 7.6-3.6 9.9-3.3 9.9.3.1 3.4-6.5 6.7-9.2 5.2-1.1 6.6-3.6 6.6-3.6s-1.5.2-2.1.2c-.8 0-1.4-.2-1.7-.3 1.3-1.2 2.4-1.5 3.5-1.7.9-.2 1.8-.4 3-1.2 2.2-1.6 1.9-5.5 1.8-5.7z"></path></g></svg>',
      globe:
        '<svg class="fill-sky-500" viewBox="0 0 24 24" aria-hidden="true" class="r-1cvl2hr r-4qtqp9 r-yyyyoo r-10ptun7 r-1d4mawv r-dnmrzs r-bnwqim r-1plcrui r-lrvibr r-1janqcz"><g><path d="M12 1.5C6.2 1.5 1.5 6.2 1.5 12S6.2 22.5 12 22.5 22.5 17.8 22.5 12 17.8 1.5 12 1.5zM9.047 5.9c-.878.484-1.22.574-1.486.858-.263.284-.663 1.597-.84 1.712-.177.115-1.462.154-1.462.154s2.148 1.674 2.853 1.832c.706.158 2.43-.21 2.77-.142.342.07 2.116 1.67 2.324 2.074.208.404.166 1.748-.038 1.944-.204.196-1.183 1.09-1.393 1.39-.21.3-1.894 4.078-2.094 4.08-.2 0-.62-.564-.73-.848-.11-.284-.427-4.012-.59-4.263-.163-.25-1.126-.82-1.276-1.026-.15-.207-.552-1.387-.527-1.617.024-.23.492-1.007.374-1.214-.117-.207-2.207-1.033-2.61-1.18-.403-.145-.983-.332-.983-.332 1.13-3.652 4.515-6.318 8.52-6.38 0 0 .125-.018.186.14.11.286.256 1.078.092 1.345-.143.23-2.21.99-3.088 1.474zm11.144 8.24c-.21-.383-1.222-2.35-1.593-2.684-.23-.208-2.2-.912-2.55-1.09-.352-.177-1.258-.997-1.267-1.213-.01-.216 1.115-1.204 1.15-1.524.056-.49-1.882-1.835-1.897-2.054-.015-.22.147-.66.31-.81.403-.36 3.19.04 3.556.36 2 1.757 3.168 4.126 3.168 6.873 0 .776-.18 1.912-.282 2.18-.08.21-.443.232-.595-.04z"></path></g></svg>',
      share: false,
    };
  },
  methods: {
    getImageWidth() {
      let img = new Image();
      img.onload = () => {
        console.log("The dimensions are " + img.width);
      };
      img.src = this.tweetImage;

      return "w-[" + img.width + "px]";
    },
    newShare() {
      this.share = true;
      console.log(this.share);
      return this.share;
    },
  },
  computed: {},
  mounted() {
    this.tweetImageWidth = this.getImageWidth();
    console.log("From mounted share value: " + this.share);
    //console.log("From mounted using computed width is: " + this.newWidth);
  },
};
</script>

<template>
  <div class="flex container mx-auto relative w-full h-screen">
    <!--Left side-bar -->
    <div class="hidden sm:block xl:w-[21.5%]">
      <div class="flex flex-col border-r-[1px] border-gray-100 pl-[18px] pr-4">
        <button
          class="
            flex
            justify-center
            hover:bg-blue-100
            w-12
            h-12
            rounded-full
            mt-1
            mb-1
          "
        >
          <img src="../assets/twitter.png" alt="" class="h-15 w-16 p-2" />
        </button>
        <button
          :key="menu.index"
          v-for="menu in sideBar"
          class="
            group
            rounded-full
            hover:bg-gray-200
            focus:font-bold
            relative
            hover:cursor-pointer
            w-12
            xl:w-full
            flex
            p-3
          "
        >
          <!-- <div
          class="bg-blue-500 absolute top-0 right-0 w-2 h-2 rounded-full"
        ></div> -->

          <div class="h-[26.5px] w-[26.5px] xl:mr-5 box-content">
            <i
              v-html="menu.icon"
              class="h-[26.5px] w-[26.5px] group-focus:hidden"
            ></i>
            <i
              v-html="menu.iconActive"
              class="hidden group-focus:block h-[26.5px] w-[26.5px]"
            ></i>
          </div>
          <p class="hidden xl:block text-xl active:semi-bold font-sans">
            {{ menu.name }}
          </p>
        </button>
        <button
          class="
            rounded-full
            hover:bg-gray-200
            focus:font-bold
            relative
            hover:cursor-pointer
            w-12
            xl:w-full
            flex
            p-3
          "
        >
          <div class="h-[26.5px] w-[26.5px] xl:mr-5 box-content">
            <i
              v-html="more.icon"
              class="h-[26.5px] w-[26.5px] group-focus:hidden"
            ></i>
          </div>
          <p class="hidden xl:block text-xl active:semi-bold font-sans">
            {{ more.name }}
          </p>
        </button>
        <button
          class="
            hidden
            xl:block
            bg-sky-500/75
            hover:bg-sky-500
            rounded-full
            w-full
            mt-3
          "
        >
          <p class="text-white font-semibold text-lg p-3">Tweet</p>
        </button>
        <button
          class="
            bg-sky-500/50
            hover:bg-sky-500
            xl:hidden
            rounded-full
            mt-3
            h-[52px]
            w-[52px]
            p-2
          "
        >
          <i v-html="mobileTweet" class="h-6 w-6"></i>
        </button>

        <button
          class="
            xl:w-full
            w-12
            h-12
            mt-4
            mb-4
            hover:bg-gray-200
            rounded-full
            flex
            items-center
            p-2
            box-content
          "
        >
          <img
            src="../assets/Cartoonify.png"
            alt=""
            class="rounded-full h-10 w-10 mr-3"
          />

          <div class="hidden xl:block">
            <p class="font-semibold whitespace-nowrap">Israel Immanuel..</p>
            <p class="text-sm text-gray-500">@IsraelImmnauel7</p>
          </div>

          <i class="hidden xl:block h-5 w-5 ml-3" v-html="threeDots"></i>
        </button>
      </div>
    </div>
    <!-- Middle content area -->
    <div
      class="
        flex flex-col
        xl:w-[48.5%]
        md:w-[56.5%]
        border-r-[1px] border-gray-100
        overflow-y-scroll
        w-full
      "
    >
      <button
        class="
          bg-sky-500/75
          hover:bg-sky-500
          sm:hidden
          rounded-full
          mt-3
          h-[52px]
          w-[52px]
          p-2
          fixed
          bottom-3
          right-5
        "
      >
        <i v-html="mobileTweet" class="h-6 w-6"></i>
      </button>
      <!-- Navbar -->
      <div
        class="
          text-lg
          font-bold
          sticky
          top-0
          bg-white
          h-12
          opacity-95
          pt-3
          pl-4
          flex
          justify-between
        "
      >
        <p class="opacity-100 text-xl">Home</p>
        <div
          class="h-5 w-5 rounded-full hover:bg-gray-500/20 mr-2 box-content p-2"
        >
          <i v-html="navStar" class="h-5 w-5"></i>
        </div>
      </div>
      <!-- Tweet Form -->
      <div class="hidden sm:block">
        <div class="mt-5 flex px-4">
          <img
            src="../assets/Cartoonify.png"
            alt=""
            class="rounded-full h-12 w-12 mr-3"
          />
          <div class="">
            <textarea
              @click="newShare"
              name=""
              id=""
              cols="30"
              rows="2"
              class="
                resize-none
                text-xl
                focus:outline-none
                w-full
                overflow-y-hidden
              "
              placeholder="What's happening?"
            ></textarea>
            <div
              v-if="share"
              class="
                hover:bg-sky-100
                rounded-full
                hover:cursor-pointer
                p-1
                pl-2
                border-b border-gray-100
                w-[55%]
                md:w-[59%]
                sm:w-[59%]
              "
            >
              <p
                class="
                  items-center
                  text-sky-500 text-sm
                  font-bold
                  flex
                  focus:bg-sky-100
                "
              >
                <i v-html="globe" class="w-4 h-4 mr-1"></i>
                <span>Everyone can reply</span>
              </p>
            </div>
          </div>
        </div>
      </div>
      <!-- Tweet Form icons -->
      <div class="hidden sm:block">
        <div class="flex justify-between items-center pr-4">
          <div class="flex ml-[74px] my-2">
            <p
              :key="index"
              v-for="(icon, index) in textAreaIcons"
              class="
                h-5
                w-5
                mr-1
                hover:bg-blue-100/50
                p-2
                rounded-full
                cursor-pointer
                box-content
              "
              v-html="icon"
            ></p>
          </div>
          <button
            v-if="!share"
            class="bg-sky-300 rounded-full my-2 py-1 px-5 font-bold text-white"
          >
            Tweet
          </button>
          <button
            v-else
            class="bg-sky-500 rounded-full my-2 py-1 px-5 font-bold text-white"
          >
            Tweet
          </button>
        </div>
      </div>
      <!-- show # tweets bar -->
      <div
        class="
          flex
          justify-center
          hover:bg-gray-100/70
          border-t border-gray-100
          text-sky-500
          py-4
          cursor-pointer
        "
      >
        <p>Show 76 Tweets</p>
      </div>

      <!-- tweets -->
      <div
        :key="index"
        v-for="(tweet, index) in tweets"
        class="
          border-y border-gray-100
          hover:bg-gray-300/20
          cursor-pointer
          flex-wrap
          w-full
        "
      >
        <!-- Tweet topic header. responsive -->
        <div class="flex items-center ml-12 mt-2">
          <i class="h-[16px] w-[16px] mr-3" v-html="chatIcon"></i>
          <p class="text-sm font-bold text-gray-500/95">
            {{ tweet.topic }} . <span class="text-sky-500/75">See more</span>
          </p>
        </div>

        <!-- Tweet. responsive-->
        <div class="flex justify-between">
          <div class="w-12 flex-none ml-4 rounded-full">
            <img
              :src="tweet.profilePicture"
              alt=""
              class="rounded-full h-12 w-12"
            />
            <!--Thread line -->
            <div v-if="tweet.thread" class="ml-6 h-full border-l-2"></div>
          </div>
          <!-- tweet -->
          <div class="pl-3">
            <div class="flex items-start">
              <p class="font-semibold mr-1">
                {{ tweet.userName }}
              </p>
              <p
                class="h-[16.41px] w-[16.41px] mt-1 mr-1"
                v-html="verifiedIcon"
              ></p>
              <p class="text-gray-500">{{ tweet.handle }}</p>
            </div>
            <p class="text-black/75 mb-3 flex">
              {{ tweet.content }}
            </p>
            <div v-if="tweet.tweetImage || tweet.tweetImageLinked">
              <img
                v-if="tweet.tweetImageLinked"
                class="rounded-t-3xl"
                :src="tweet.tweetImageLinked"
                alt=""
              />
              <img v-else class="rounded-3xl" :src="tweet.tweetImage" alt="" />
              <div
                v-if="tweet.tweetImageLinked"
                class="
                  bg-g-white
                  rounded-b-2xl
                  px-3
                  py-2
                  border border-gray-300/80
                "
                :class="tweetImageWidth"
              >
                <p class="text-gray-500/80">{{ tweet.siteUrl }}</p>
                <p class="text-black/80">{{ tweet.siteHeading }}</p>
                <p class="text-gray-500/95">{{ tweet.siteData }}</p>
              </div>
            </div>
            <div class="flex mb-1 justify-between w-[85%]">
              <div class="mt-2 flex items-center group justify-between">
                <i
                  class="
                    group-hover:bg-blue-100
                    h-[34.75px]
                    w-[34.75px]
                    rounded-full
                    p-2
                  "
                  v-html="tweetIcons.comment"
                ></i>
                <p class="text-sm text-gray-500 group-hover:text-blue-500">
                  {{ tweet.comment }}
                </p>
              </div>
              <div class="mt-2 flex items-center group justify-between">
                <i
                  class="
                    h-[34.75px]
                    w-[34.75px]
                    rounded-full
                    group-hover:bg-green-100
                    p-2
                  "
                  v-html="tweetIcons.retweet"
                ></i>
                <p class="text-sm text-gray-500 group-hover:text-green-500">
                  {{ tweet.retweets }}
                </p>
              </div>
              <div class="mt-2 flex items-center group justify-between">
                <i
                  class="
                    h-[34.75px]
                    w-[34.75px]
                    rounded-full
                    group-hover:bg-pink-100
                    p-2
                  "
                  v-html="tweetIcons.like"
                ></i>
                <p class="text-sm text-gray-500 group-hover:text-pink-500">
                  {{ tweet.likes }}
                </p>
              </div>
              <div class="mt-2 flex items-center group">
                <i
                  class="
                    h-[34.75px]
                    w-[34.75px]
                    rounded-full
                    group-hover:bg-blue-100
                    p-2
                    mr-1
                  "
                  v-html="tweetIcons.share"
                ></i>
              </div>
            </div>
            <div v-if="tweet.promoted" class="h-4 flex items-center">
              <i class="mr-1 w-[15px] h-[15px]" v-html="promotedIcon"></i>
              <p class="text-sm text-black/75">Promoted</p>
            </div>
          </div>
          <!-- ThreeDots -->
          <div
            class="
              h-full
              w-[]
              mr-
              hover:bg-blue-100/50
              rounded-full
              flex
              items-center
              p-1
            "
          >
            <i v-html="threeDots" class="h-[15.75px] w-[15.75px]"></i>
          </div>
        </div>
        <!-- Tweet thread area -->
        <div
          v-if="tweet.thread"
          class="w-full items-center flex pl-6 hover:bg-gray-300/30 py-2"
        >
          <div class="w-12">
            <img
              :src="tweet.profilePicture"
              alt=""
              class="rounded-full h-8 w-8"
            />
          </div>
          <div class="pl-3">
            <p class="text-sky-500">Show this thread</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Right side-bar -->
    <div
      class="
        hidden
        lg:block
        pl-10
        pr-4
        mt-2
        xl:w-[30%]
        md:w-[44.5%]
        overflow-y-scroll
      "
    >
      <div class="bg-white">
        <div class="fixed top-0 bg-white pb-2 pt-1 w-[30%] lg:w-full">
          <p class="text-gray-400 absolute top-[16px] left-4">
            <svg
              width="24"
              height="24"
              fill="none"
              aria-hidden="true"
              class="mr-3 flex-none"
            >
              <path
                d="m19 19-3.5-3.5"
                stroke="currentColor"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <circle
                cx="11"
                cy="11"
                r="6"
                stroke="currentColor"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></circle>
            </svg>
          </p>
          <input
            type="text"
            class="
              bg-gray-300/30
              rounded-full
              p-[11px]
              pl-14
              placeholder-gray-400
              hover:outline-none
              focus:outline-none
              focus:bg-white
              focus:border
              focus:border-blue-300
            "
            placeholder="Search Twitter"
          />
        </div>
      </div>

      <div class="rounded-xl mt-14 bg-gray-300/20 pt-2">
        <p class="font-bold text-xl ml-5 mb-4">Kenya trends</p>
        <div class="flex flex-col">
          <button
            :key="index"
            v-for="(topic, index) in trending"
            class="flex justify-between hover:bg-gray-300/20 p-2 pl-5"
          >
            <div class="">
              <p class="text-gray-500/80 text-sm flex items-start">
                {{ index }} . Trending
              </p>
              <p class="text-md font-semibold">{{ topic.trend }}</p>
              <p class="text-gray-500/80 text-sm flex items-start">
                {{ topic.number }}
              </p>
            </div>

            <p
              v-html="threeDots"
              class="h-10 w-10 hover:bg-blue-100/50 rounded-full p-3"
            ></p>
          </button>
          <button class="flex items-center hover:bg-gray-300/20 p-3 pl-5">
            <p class="text-sky-500 flex items-start">Show more</p>
          </button>
        </div>
      </div>

      <div class="rounded-xl mt-5 bg-gray-300/20 pt-2">
        <p class="font-bold text-xl ml-5 mb-3">Who to follow</p>
        <div class="flex flex-col">
          <button
            class="flex justify-between items-center hover:bg-gray-300/20 p-2"
          >
            <div class="flex items-center p-2">
              <img
                src="../assets/man.jpg"
                alt=""
                class="rounded-full h-10 w-10 mr-3"
              />

              <div class="flex flex-col items-start">
                <p class="font-semibold whitespace-nowrap">Otieno Omondi..</p>
                <p class="text-sm text-gray-500">@otisOmosh88</p>
              </div>
            </div>
            <div class="bg-black hover:bg-black/70 rounded-full w-3/12">
              <p class="text-white font-semibold p-1">Follow</p>
            </div>
          </button>
          <button
            class="flex justify-between items-center hover:bg-gray-300/20 p-2"
          >
            <div class="flex items-center p-2">
              <img
                src="../assets/lady.jpg"
                alt=""
                class="rounded-full h-10 w-10 mr-3"
              />

              <div class="flex flex-col items-start">
                <p class="font-semibold whitespace-nowrap">Tena lulu..</p>
                <p class="text-sm text-gray-500">
                  @Itenalulu33<span
                    class="
                      text-black/75 text-xs
                      font-semibold
                      bg-gray-300/40
                      ml-1
                      rounded-md
                      px-1
                    "
                    >Follows you</span
                  >
                </p>
              </div>
            </div>
            <div class="bg-black hover:bg-black/70 rounded-full w-3/12">
              <p class="text-white font-semibold p-1">Follow</p>
            </div>
          </button>
          <button
            class="flex justify-between items-center hover:bg-gray-300/20 p-2"
          >
            <div class="flex items-center p-2">
              <img
                src="../assets/lady1.jpg"
                alt=""
                class="rounded-full h-10 w-10 mr-3"
              />

              <div class="flex flex-col items-start">
                <p class="font-semibold whitespace-nowrap">Katse Muriri..</p>
                <p class="text-sm text-gray-500">
                  @KatseMuriri<span
                    class="
                      text-black/75 text-xs
                      font-semibold
                      bg-gray-300/40
                      ml-1
                      rounded-lg
                      px-1
                    "
                    >Follows you</span
                  >
                </p>
              </div>
            </div>
            <div class="bg-black hover:bg-black/70 rounded-full w-3/12">
              <p class="text-white font-semibold p-1">Follow</p>
            </div>
          </button>
          <button class="flex items-center hover:bg-gray-300/20 p-3 pl-5">
            <p class="text-sky-500 flex items-start">Show more</p>
          </button>
        </div>
      </div>

      <div class="mt-4 mb-5 pr-10">
        <div class="flex justify-between">
          <p class="cursor-pointer hover:underline text-sm text-gray-500">
            Terms of service
          </p>
          <p class="cursor-pointer hover:underline text-sm text-gray-500">
            Privacy Policy
          </p>
          <p class="cursor-pointer hover:underline text-sm text-gray-500">
            Cookie Policy
          </p>
        </div>
        <div class="flex justify-between pr-24">
          <p class="cursor-pointer hover:underline text-sm text-gray-500">
            Accessibility
          </p>
          <p class="cursor-pointer hover:underline text-sm text-gray-500">
            Ads info
          </p>
          <p class="cursor-pointer hover:underline text-sm text-gray-500">
            More...
          </p>
        </div>
        <p class="text-sm text-gray-500">&copy;2022 Twitter, Inc.</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
/* width */
::-webkit-scrollbar {
  width: 5px;
}
</style>
