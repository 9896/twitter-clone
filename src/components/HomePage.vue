<script>
export default {
  data() {
    return {
      sideBar: {
        Home: {
          icon: '<svg viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-lwhw9o r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><path d="M22.46 7.57L12.357 2.115c-.223-.12-.49-.12-.713 0L1.543 7.57c-.364.197-.5.652-.303 1.017.135.25.394.393.66.393.12 0 .243-.03.356-.09l.815-.44L4.7 19.963c.214 1.215 1.308 2.062 2.658 2.062h9.282c1.352 0 2.445-.848 2.663-2.087l1.626-11.49.818.442c.364.193.82.06 1.017-.304.196-.363.06-.818-.304-1.016zm-4.638 12.133c-.107.606-.703.822-1.18.822H7.36c-.48 0-1.075-.216-1.178-.798L4.48 7.69 12 3.628l7.522 4.06-1.7 12.015z"></path><path d="M8.22 12.184c0 2.084 1.695 3.78 3.78 3.78s3.78-1.696 3.78-3.78-1.695-3.78-3.78-3.78-3.78 1.696-3.78 3.78zm6.06 0c0 1.258-1.022 2.28-2.28 2.28s-2.28-1.022-2.28-2.28 1.022-2.28 2.28-2.28 2.28 1.022 2.28 2.28z"></path></g></svg>',
          name: "Home",
        },
        Explore: {
          icon: '<svg viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-lwhw9o r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><path d="M21.53 20.47l-3.66-3.66C19.195 15.24 20 13.214 20 11c0-4.97-4.03-9-9-9s-9 4.03-9 9 4.03 9 9 9c2.215 0 4.24-.804 5.808-2.13l3.66 3.66c.147.146.34.22.53.22s.385-.073.53-.22c.295-.293.295-.767.002-1.06zM3.5 11c0-4.135 3.365-7.5 7.5-7.5s7.5 3.365 7.5 7.5-3.365 7.5-7.5 7.5-7.5-3.365-7.5-7.5z"></path></g></svg>',
          name: "Explore",
        },
        Notifications: {
          icon: '<svg viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-lwhw9o r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><path d="M21.697 16.468c-.02-.016-2.14-1.64-2.103-6.03.02-2.532-.812-4.782-2.347-6.335C15.872 2.71 14.01 1.94 12.005 1.93h-.013c-2.004.01-3.866.78-5.242 2.174-1.534 1.553-2.368 3.802-2.346 6.334.037 4.33-2.02 5.967-2.102 6.03-.26.193-.366.53-.265.838.102.308.39.515.712.515h4.92c.102 2.31 1.997 4.16 4.33 4.16s4.226-1.85 4.327-4.16h4.922c.322 0 .61-.206.71-.514.103-.307-.003-.645-.263-.838zM12 20.478c-1.505 0-2.73-1.177-2.828-2.658h5.656c-.1 1.48-1.323 2.66-2.828 2.66zM4.38 16.32c.74-1.132 1.548-3.028 1.524-5.896-.018-2.16.644-3.982 1.913-5.267C8.91 4.05 10.397 3.437 12 3.43c1.603.008 3.087.62 4.18 1.728 1.27 1.285 1.933 3.106 1.915 5.267-.024 2.868.785 4.765 1.525 5.896H4.38z"></path></g></svg>',
          name: "Notifications",
        },
        Messages: {
          icon: '<svg viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-lwhw9o r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><path d="M19.25 3.018H4.75C3.233 3.018 2 4.252 2 5.77v12.495c0 1.518 1.233 2.753 2.75 2.753h14.5c1.517 0 2.75-1.235 2.75-2.753V5.77c0-1.518-1.233-2.752-2.75-2.752zm-14.5 1.5h14.5c.69 0 1.25.56 1.25 1.25v.714l-8.05 5.367c-.273.18-.626.182-.9-.002L3.5 6.482v-.714c0-.69.56-1.25 1.25-1.25zm14.5 14.998H4.75c-.69 0-1.25-.56-1.25-1.25V8.24l7.24 4.83c.383.256.822.384 1.26.384.44 0 .877-.128 1.26-.383l7.24-4.83v10.022c0 .69-.56 1.25-1.25 1.25z"></path></g></svg>',
          name: "Messages",
        },
        Bookmarks: {
          icon: '<svg viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-lwhw9o r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><path d="M19.9 23.5c-.157 0-.312-.05-.442-.144L12 17.928l-7.458 5.43c-.228.164-.53.19-.782.06-.25-.127-.41-.385-.41-.667V5.6c0-1.24 1.01-2.25 2.25-2.25h12.798c1.24 0 2.25 1.01 2.25 2.25v17.15c0 .282-.158.54-.41.668-.106.055-.223.082-.34.082zM12 16.25c.155 0 .31.048.44.144l6.71 4.883V5.6c0-.412-.337-.75-.75-.75H5.6c-.413 0-.75.338-.75.75v15.677l6.71-4.883c.13-.096.285-.144.44-.144z"></path></g></svg>',
          name: "Bookmarks",
        },
        Lists: {
          icon: '<svg viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-lwhw9o r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><path d="M19.75 22H4.25C3.01 22 2 20.99 2 19.75V4.25C2 3.01 3.01 2 4.25 2h15.5C20.99 2 22 3.01 22 4.25v15.5c0 1.24-1.01 2.25-2.25 2.25zM4.25 3.5c-.414 0-.75.337-.75.75v15.5c0 .413.336.75.75.75h15.5c.414 0 .75-.337.75-.75V4.25c0-.413-.336-.75-.75-.75H4.25z"></path><path d="M17 8.64H7c-.414 0-.75-.337-.75-.75s.336-.75.75-.75h10c.414 0 .75.335.75.75s-.336.75-.75.75zm0 4.11H7c-.414 0-.75-.336-.75-.75s.336-.75.75-.75h10c.414 0 .75.336.75.75s-.336.75-.75.75zm-5 4.11H7c-.414 0-.75-.335-.75-.75s.336-.75.75-.75h5c.414 0 .75.337.75.75s-.336.75-.75.75z"></path></g></svg>',
          name: "Lists",
        },
        Profile: {
          icon: '<svg viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-lwhw9o r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><path d="M12 11.816c1.355 0 2.872-.15 3.84-1.256.814-.93 1.078-2.368.806-4.392-.38-2.825-2.117-4.512-4.646-4.512S7.734 3.343 7.354 6.17c-.272 2.022-.008 3.46.806 4.39.968 1.107 2.485 1.256 3.84 1.256zM8.84 6.368c.162-1.2.787-3.212 3.16-3.212s2.998 2.013 3.16 3.212c.207 1.55.057 2.627-.45 3.205-.455.52-1.266.743-2.71.743s-2.255-.223-2.71-.743c-.507-.578-.657-1.656-.45-3.205zm11.44 12.868c-.877-3.526-4.282-5.99-8.28-5.99s-7.403 2.464-8.28 5.99c-.172.692-.028 1.4.395 1.94.408.52 1.04.82 1.733.82h12.304c.693 0 1.325-.3 1.733-.82.424-.54.567-1.247.394-1.94zm-1.576 1.016c-.126.16-.316.246-.552.246H5.848c-.235 0-.426-.085-.552-.246-.137-.174-.18-.412-.12-.654.71-2.855 3.517-4.85 6.824-4.85s6.114 1.994 6.824 4.85c.06.242.017.48-.12.654z"></path></g></svg>',
          name: "Profile",
        },
        more: {
          icon: '<svg viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-lwhw9o r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><circle cx="17" cy="12" r="1.5"></circle><circle cx="12" cy="12" r="1.5"></circle><circle cx="7" cy="12" r="1.5"></circle><path d="M12 22.75C6.072 22.75 1.25 17.928 1.25 12S6.072 1.25 12 1.25 22.75 6.072 22.75 12 17.928 22.75 12 22.75zm0-20C6.9 2.75 2.75 6.9 2.75 12S6.9 21.25 12 21.25s9.25-4.15 9.25-9.25S17.1 2.75 12 2.75z"></path></g></svg>',
          name: "More",
        },
      },
      threeDots:
        '<svg viewBox="0 0 24 24" aria-hidden="true" class="r-18jsvk2 r-4qtqp9 r-yyyyoo r-1xvli5t r-dnmrzs r-bnwqim r-1plcrui r-lrvibr"><g><circle cx="5" cy="12" r="2"></circle><circle cx="12" cy="12" r="2"></circle><circle cx="19" cy="12" r="2"></circle></g></svg>',
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
    };
  },
};
</script>

<template>
  <div class="flex">
    <!--Left side-bar -->
    <div
      class="flex flex-col w-[320px] border-r-[1px] border-gray-110 pl-14 pr-4"
    >
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
        class="rounded-full hover:bg-gray-200 focus:font-bold"
      >
        <div class="flex p-3">
          <i v-html="menu.icon" class="h-7 w-7 mr-5"></i>
          <p class="text-xl active:semi-bold font-sans">{{ menu.name }}</p>
        </div>
      </button>
      <button class="bg-sky-500/75 hover:bg-sky-500 rounded-full w-full mt-3">
        <p class="text-white font-semibold text-lg p-3">Tweet</p>
      </button>

      <button class="mt-4 mb-4 hover:bg-gray-200 rounded-full">
        <div class="flex items-center p-2">
          <img
            src="../assets/Cartoonify.png"
            alt=""
            class="rounded-full h-10 w-10 mr-3"
          />

          <div>
            <p class="font-semibold whitespace-nowrap">Israel Immanuel..</p>
            <p class="text-sm text-gray-500">@IsraelImmnauel7</p>
          </div>

          <i v-html="threeDots" class="h-5 w-5 ml-3"></i>
        </div>
      </button>
    </div>

    <!-- Middle content area -->
    <div
      class="
        flex flex-col
        w-[595px]
        border-r-[1px] border-gray-110
        pl-4
        pr-4
        
      "
    >
      <p class="text-lg font-bold sticky top-0 bg-white h-12 opacity-95 pt-3"><span class="opacity-100">Home</span></p>
      <div class="mt-5 flex">
        <img
          src="../assets/Cartoonify.png"
          alt=""
          class="rounded-full h-12 w-12 mr-3"
        />
        <p class="text-xl w-full overflow-y-hidden">
        <textarea
          name=""
          id=""
          cols="30"
          rows="3"
          class="w-full resize-none border-b border-gray-100 focus:outline-none"
          placeholder="What's happening?"
        ></textarea>
        </p>
      </div>
    </div>

    <!-- Right side-bar -->
    <div class="pl-10 pr-14 mt-2 w-[434px] overflow-y-auto">
      <div class="w-full relative bg-white">
        <div class="fixed top-0 bg-white w-full pb-2 pt-1">
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
            focus:outline-none focus:bg-white focus:border focus:border-blue-300
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
                      text-gray-500 text-xs
                      bg-gray-300/40
                      ml-1
                      rounded-lg
                      p-1
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
                      text-gray-500 text-xs
                      bg-gray-300/40
                      ml-1
                      rounded-lg
                      p-1
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
        <p class="text-sm text-gray-500">&copy; Twitter, Inc.</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
</style>
