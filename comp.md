
import './App.css'
import { AnimatedPinDemo } from './components/AnimatedPinDemo'
import { TextGenerateEffectDemo } from './components/TextGenerateEffectDemo'
import { ContainerScroll } from './components/ui/container-scroll-animation'
// import { ContainerScroll } from './components/ui/container-scroll-animation'
// import { HeroScrollDemo } from './components/ui/HeroScrollDemo'
function App() {


  return (
    <>
      //c1
      <div class="p-4 bg-white shadow-lg rounded-2xl dark:bg-gray-800">
        <div class="flex items-center">
          <span class="relative p-4 bg-purple-200 rounded-xl">
            <svg width="40" fill="currentColor" height="40" class="absolute h-4 text-purple-500 transform -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg">
              <path d="M1362 1185q0 153-99.5 263.5t-258.5 136.5v175q0 14-9 23t-23 9h-135q-13 0-22.5-9.5t-9.5-22.5v-175q-66-9-127.5-31t-101.5-44.5-74-48-46.5-37.5-17.5-18q-17-21-2-41l103-135q7-10 23-12 15-2 24 9l2 2q113 99 243 125 37 8 74 8 81 0 142.5-43t61.5-122q0-28-15-53t-33.5-42-58.5-37.5-66-32-80-32.5q-39-16-61.5-25t-61.5-26.5-62.5-31-56.5-35.5-53.5-42.5-43.5-49-35.5-58-21-66.5-8.5-78q0-138 98-242t255-134v-180q0-13 9.5-22.5t22.5-9.5h135q14 0 23 9t9 23v176q57 6 110.5 23t87 33.5 63.5 37.5 39 29 15 14q17 18 5 38l-81 146q-8 15-23 16-14 3-27-7-3-3-14.5-12t-39-26.5-58.5-32-74.5-26-85.5-11.5q-95 0-155 43t-60 111q0 26 8.5 48t29.5 41.5 39.5 33 56 31 60.5 27 70 27.5q53 20 81 31.5t76 35 75.5 42.5 62 50 53 63.5 31.5 76.5 13 94z">
              </path>
            </svg>
          </span>
          <p class="ml-2 text-black text-md dark:text-white">
            Finance
          </p>
        </div>
        <div class="flex flex-col justify-start">
          <p class="my-4 text-4xl font-bold text-left text-gray-700 dark:text-gray-100">
            34,500
            <span class="text-sm">
              Rs
            </span>
          </p>
          <div class="flex items-center text-sm text-green-500">
            <svg width="20" height="20" fill="currentColor" viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg">
              <path d="M1408 1216q0 26-19 45t-45 19h-896q-26 0-45-19t-19-45 19-45l448-448q19-19 45-19t45 19l448 448q19 19 19 45z">
              </path>
            </svg>
            <span>
              5.5%
            </span>
            <span class="text-gray-400">
              vs last month
            </span>
          </div>
        </div>
      </div>
      //c2

      {/* <div class="p-4 bg-white shadow-lg rounded-2xl dark:bg-gray-700">
        <div class="flex flex-wrap overflow-hidden">
          <div class="w-full rounded shadow-sm">
            <div class="flex items-center justify-between mb-4">
              <div class="text-xl font-bold text-left text-black dark:text-white">
                Dec 2021
              </div>
              <div class="flex space-x-4">
                <button class="p-2 text-white bg-blue-500 rounded-full">
                  <svg width="15" height="15" fill="currentColor" viewBox="0 0 24 24">
                    <path fill="currentColor" d="M13.83 19a1 1 0 0 1-.78-.37l-4.83-6a1 1 0 0 1 0-1.27l5-6a1 1 0 0 1 1.54 1.28L10.29 12l4.32 5.36a1 1 0 0 1-.78 1.64z">
                    </path>
                  </svg>
                </button>
                <button class="p-2 text-white bg-blue-500 rounded-full">
                  <svg width="15" height="15" fill="currentColor" viewBox="0 0 24 24">
                    <path fill="currentColor" d="M10 19a1 1 0 0 1-.64-.23a1 1 0 0 1-.13-1.41L13.71 12L9.39 6.63a1 1 0 0 1 .15-1.41a1 1 0 0 1 1.46.15l4.83 6a1 1 0 0 1 0 1.27l-5 6A1 1 0 0 1 10 19z">
                    </path>
                  </svg>
                </button>
              </div>
            </div>
            <div class="-mx-2">
              <table class="w-full dark:text-white">
                <tr>
                  <th class="px-2 py-3 md:px-3 ">
                    S
                  </th>
                  <th class="px-2 py-3 md:px-3 ">
                    M
                  </th>
                  <th class="px-2 py-3 md:px-3 ">
                    T
                  </th>
                  <th class="px-2 py-3 md:px-3 ">
                    W
                  </th>
                  <th class="px-2 py-3 md:px-3 ">
                    T
                  </th>
                  <th class="px-2 py-3 md:px-3 ">
                    F
                  </th>
                  <th class="px-2 py-3 md:px-3 ">
                    S
                  </th>
                </tr>
                <tr class="text-gray-400 dark:text-gray-500">
                  <td class="px-2 py-3 text-center text-gray-300 md:px-3 dark:text-gray-500">
                    25
                  </td>
                  <td class="px-2 py-3 text-center text-gray-300 md:px-3 dark:text-gray-500">
                    26
                  </td>
                  <td class="px-2 py-3 text-center text-gray-300 md:px-3 dark:text-gray-500">
                    27
                  </td>
                  <td class="px-2 py-3 text-center text-gray-300 md:px-3 dark:text-gray-500">
                    28
                  </td>
                  <td class="px-2 py-3 text-center text-gray-300 md:px-3 dark:text-gray-500">
                    29
                  </td>
                  <td class="px-2 py-3 text-center text-gray-300 md:px-3 dark:text-gray-500">
                    30
                  </td>
                  <td class="px-2 py-3 text-center text-gray-800 cursor-pointer md:px-3 hover:text-blue-500">
                    1
                  </td>
                </tr>
                <tr>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    2
                  </td>
                  <td class="relative px-1 py-3 text-center cursor-pointer hover:text-blue-500">
                    3
                    <span class="absolute bottom-0 w-2 h-2 transform -translate-x-1/2 bg-blue-500 rounded-full left-1/2">
                    </span>
                  </td>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    4
                  </td>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    5
                  </td>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    6
                  </td>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    7
                  </td>
                  <td class="relative px-2 py-3 text-center cursor-pointer md:px-3 lg:px-3 hover:text-blue-500">
                    8
                    <span class="absolute bottom-0 w-2 h-2 transform -translate-x-1/2 bg-yellow-500 rounded-full left-1/2">
                    </span>
                  </td>
                </tr>
                <tr>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    9
                  </td>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    10
                  </td>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    11
                  </td>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    12
                  </td>
                  <td class="px-2 py-3 text-center text-white cursor-pointer md:px-3">
                    <span class="p-2 bg-blue-500 rounded-full">
                      13
                    </span>
                  </td>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    14
                  </td>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    15
                  </td>
                </tr>
                <tr>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    16
                  </td>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    17
                  </td>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    18
                  </td>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    19
                  </td>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    20
                  </td>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    21
                  </td>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    22
                  </td>
                </tr>
                <tr>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    23
                  </td>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    24
                  </td>
                  <td class="relative px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    25
                    <span class="absolute bottom-0 w-2 h-2 transform -translate-x-1/2 bg-red-500 rounded-full left-1/2">
                    </span>
                  </td>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    26
                  </td>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    27
                  </td>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    28
                  </td>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    29
                  </td>
                </tr>
                <tr>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    30
                  </td>
                  <td class="px-2 py-3 text-center cursor-pointer md:px-3 hover:text-blue-500">
                    31
                  </td>
                  <td>
                  </td>
                  <td>
                  </td>
                  <td>
                  </td>
                  <td>
                  </td>
                  <td>
                  </td>
                </tr>
              </table>
            </div>
          </div>
        </div>
      </div> */}
      //c3

      <div class="p-4 bg-white shadow-lg rounded-2xl w-36 dark:bg-gray-800">
        <div class="flex items-center">
          <span class="relative w-4 h-4 p-2 bg-green-500 rounded-full">
            <svg width="20" fill="currentColor" height="20" class="absolute h-2 text-white transform -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg">
              <path d="M1362 1185q0 153-99.5 263.5t-258.5 136.5v175q0 14-9 23t-23 9h-135q-13 0-22.5-9.5t-9.5-22.5v-175q-66-9-127.5-31t-101.5-44.5-74-48-46.5-37.5-17.5-18q-17-21-2-41l103-135q7-10 23-12 15-2 24 9l2 2q113 99 243 125 37 8 74 8 81 0 142.5-43t61.5-122q0-28-15-53t-33.5-42-58.5-37.5-66-32-80-32.5q-39-16-61.5-25t-61.5-26.5-62.5-31-56.5-35.5-53.5-42.5-43.5-49-35.5-58-21-66.5-8.5-78q0-138 98-242t255-134v-180q0-13 9.5-22.5t22.5-9.5h135q14 0 23 9t9 23v176q57 6 110.5 23t87 33.5 63.5 37.5 39 29 15 14q17 18 5 38l-81 146q-8 15-23 16-14 3-27-7-3-3-14.5-12t-39-26.5-58.5-32-74.5-26-85.5-11.5q-95 0-155 43t-60 111q0 26 8.5 48t29.5 41.5 39.5 33 56 31 60.5 27 70 27.5q53 20 81 31.5t76 35 75.5 42.5 62 50 53 63.5 31.5 76.5 13 94z">
              </path>
            </svg>
          </span>
          <p class="ml-2 text-gray-700 text-md dark:text-gray-50">
            Sales
          </p>
        </div>
        <div class="flex flex-col justify-start">
          <p class="my-4 text-4xl font-bold text-left text-gray-800 dark:text-white">
            3600 Orders
          </p>
          <div class="relative h-2 bg-gray-200 rounded w-28">
            <div class="absolute top-0 left-0 w-2/3 h-2 bg-green-500 rounded">
            </div>
          </div>
        </div>
      </div>
      //c4

      {/* <div class="p-8 bg-white rounded-lg shadow dark:bg-gray-800">
        <p class="text-3xl font-bold text-center text-gray-800 dark:text-white">
          Professional team
        </p>
        <p class="mb-12 text-xl font-normal text-center text-gray-500 dark:text-gray-200">
          Meat the best team in wolrd
        </p>
        <div class="flex flex-col items-center md:flex-row justify evenly">
          <div class="p-4">
            <div class="mb-4 text-center opacity-90">
              <a href="#" class="relative block">
                <img alt="profil" src="/images/person/1.jpg" class="mx-auto object-cover rounded-full h-40 w-40 " />
              </a>
            </div>
            <div class="text-center">
              <p class="text-2xl text-gray-800 dark:text-white">
                Patrick Sebastien
              </p>
              <p class="text-xl font-light text-gray-500 dark:text-gray-200">
                Developpeur
              </p>
              <p class="max-w-xs py-4 font-light text-gray-500 text-md dark:text-gray-400">
                Patrick Sébastien, born November 14, 1953 in Brive-la-Gaillarde, is an imitator.
              </p>
            </div>
            <div class="flex items-center justify-between pt-8 mx-auto text-gray-500 border-t border-gray-200 w-44">
              <a href="#">
                <svg width="30" height="30" fill="currentColor" class="text-xl transition-colors duration-200 hover:text-gray-800 dark:hover:text-white" viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg">
                  <path d="M1343 12v264h-157q-86 0-116 36t-30 108v189h293l-39 296h-254v759h-306v-759h-255v-296h255v-218q0-186 104-288.5t277-102.5q147 0 228 12z">
                  </path>
                </svg>
              </a>
              <a href="#">
                <svg width="30" height="30" fill="currentColor" class="text-xl transition-colors duration-200 hover:text-gray-800 dark:hover:text-white" viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg">
                  <path d="M1684 408q-67 98-162 167 1 14 1 42 0 130-38 259.5t-115.5 248.5-184.5 210.5-258 146-323 54.5q-271 0-496-145 35 4 78 4 225 0 401-138-105-2-188-64.5t-114-159.5q33 5 61 5 43 0 85-11-112-23-185.5-111.5t-73.5-205.5v-4q68 38 146 41-66-44-105-115t-39-154q0-88 44-163 121 149 294.5 238.5t371.5 99.5q-8-38-8-74 0-134 94.5-228.5t228.5-94.5q140 0 236 102 109-21 205-78-37 115-142 178 93-10 186-50z">
                  </path>
                </svg>
              </a>
              <a href="#">
                <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="currentColor" class="text-xl transition-colors duration-200 hover:text-gray-800 dark:hover:text-white" viewBox="0 0 1792 1792">
                  <path d="M896 128q209 0 385.5 103t279.5 279.5 103 385.5q0 251-146.5 451.5t-378.5 277.5q-27 5-40-7t-13-30q0-3 .5-76.5t.5-134.5q0-97-52-142 57-6 102.5-18t94-39 81-66.5 53-105 20.5-150.5q0-119-79-206 37-91-8-204-28-9-81 11t-92 44l-38 24q-93-26-192-26t-192 26q-16-11-42.5-27t-83.5-38.5-85-13.5q-45 113-8 204-79 87-79 206 0 85 20.5 150t52.5 105 80.5 67 94 39 102.5 18q-39 36-49 103-21 10-45 15t-57 5-65.5-21.5-55.5-62.5q-19-32-48.5-52t-49.5-24l-20-3q-21 0-29 4.5t-5 11.5 9 14 13 12l7 5q22 10 43.5 38t31.5 51l10 23q13 38 44 61.5t67 30 69.5 7 55.5-3.5l23-4q0 38 .5 88.5t.5 54.5q0 18-13 30t-40 7q-232-77-378.5-277.5t-146.5-451.5q0-209 103-385.5t279.5-279.5 385.5-103zm-477 1103q3-7-7-12-10-3-13 2-3 7 7 12 9 6 13-2zm31 34q7-5-2-16-10-9-16-3-7 5 2 16 10 10 16 3zm30 45q9-7 0-19-8-13-17-6-9 5 0 18t17 7zm42 42q8-8-4-19-12-12-20-3-9 8 4 19 12 12 20 3zm57 25q3-11-13-16-15-4-19 7t13 15q15 6 19-6zm63 5q0-13-17-11-16 0-16 11 0 13 17 11 16 0 16-11zm58-10q-2-11-18-9-16 3-14 15t18 8 14-14z">
                  </path>
                </svg>
              </a>
              <a href="#">
                <svg width="30" height="30" fill="currentColor" class="text-xl transition-colors duration-200 hover:text-gray-800 dark:hover:text-white" viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg">
                  <path d="M477 625v991h-330v-991h330zm21-306q1 73-50.5 122t-135.5 49h-2q-82 0-132-49t-50-122q0-74 51.5-122.5t134.5-48.5 133 48.5 51 122.5zm1166 729v568h-329v-530q0-105-40.5-164.5t-126.5-59.5q-63 0-105.5 34.5t-63.5 85.5q-11 30-11 81v553h-329q2-399 2-647t-1-296l-1-48h329v144h-2q20-32 41-56t56.5-52 87-43.5 114.5-15.5q171 0 275 113.5t104 332.5z">
                  </path>
                </svg>
              </a>
              <a href="#">
                <svg width="30" height="30" fill="currentColor" class="text-xl transition-colors duration-200 hover:text-gray-800 dark:hover:text-white" viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg">
                  <path d="M1551 1476q15-6 26-3t11 17.5-15 33.5q-13 16-44 43.5t-95.5 68-141 74-188 58-229.5 24.5q-119 0-238-31t-209-76.5-172.5-104-132.5-105-84-87.5q-8-9-10-16.5t1-12 8-7 11.5-2 11.5 4.5q192 117 300 166 389 176 799 90 190-40 391-135zm207-115q11 16 2.5 69.5t-28.5 102.5q-34 83-85 124-17 14-26 9t0-24q21-45 44.5-121.5t6.5-98.5q-5-7-15.5-11.5t-27-6-29.5-2.5-35 0-31.5 2-31 3-22.5 2q-6 1-13 1.5t-11 1-8.5 1-7 .5h-10l-3-.5-2-1.5-1.5-3q-6-16 47-40t103-30q46-7 108-1t76 24zm-394-443q0 31 13.5 64t32 58 37.5 46 33 32l13 11-227 224q-40-37-79-75.5t-58-58.5l-19-20q-11-11-25-33-38 59-97.5 102.5t-127.5 63.5-140 23-137.5-21-117.5-65.5-83-113-31-162.5q0-84 28-154t72-116.5 106.5-83 122.5-57 130-34.5 119.5-18.5 99.5-6.5v-127q0-65-21-97-34-53-121-53-6 0-16.5 1t-40.5 12-56 29.5-56 59.5-48 96l-294-27q0-60 22-119t67-113 108-95 151.5-65.5 190.5-24.5q100 0 181 25t129.5 61.5 81 83 45 86 12.5 73.5v589zm-672 21q0 86 70 133 66 44 139 22 84-25 114-123 14-45 14-101v-162q-59 2-111 12t-106.5 33.5-87 71-32.5 114.5z">
                  </path>
                </svg>
              </a>
            </div>
          </div>
          <div class="p-4">
            <div class="mb-4 text-center opacity-90">
              <a href="#" class="relative block">
                <img alt="profil" src="/images/person/4.jpg" class="mx-auto object-cover rounded-full h-40 w-40 " />
              </a>
            </div>
            <div class="text-center">
              <p class="text-2xl text-gray-800 dark:text-white">
                Jean Castux
              </p>
              <p class="text-xl font-light text-gray-500 dark:text-gray-200">
                Founder
              </p>
              <p class="max-w-xs py-4 font-light text-gray-500 text-md dark:text-gray-400">
                Jean Castux is an imitator, humorist, actor, born November 14, 1953 in Pontivy.
              </p>
            </div>
            <div class="flex items-center justify-between pt-8 mx-auto text-gray-500 border-t border-gray-200 w-44">
              <a href="#">
                <svg width="30" height="30" fill="currentColor" class="text-xl transition-colors duration-200 hover:text-gray-800 dark:hover:text-white" viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg">
                  <path d="M1343 12v264h-157q-86 0-116 36t-30 108v189h293l-39 296h-254v759h-306v-759h-255v-296h255v-218q0-186 104-288.5t277-102.5q147 0 228 12z">
                  </path>
                </svg>
              </a>
              <a href="#">
                <svg width="30" height="30" fill="currentColor" class="text-xl transition-colors duration-200 hover:text-gray-800 dark:hover:text-white" viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg">
                  <path d="M1684 408q-67 98-162 167 1 14 1 42 0 130-38 259.5t-115.5 248.5-184.5 210.5-258 146-323 54.5q-271 0-496-145 35 4 78 4 225 0 401-138-105-2-188-64.5t-114-159.5q33 5 61 5 43 0 85-11-112-23-185.5-111.5t-73.5-205.5v-4q68 38 146 41-66-44-105-115t-39-154q0-88 44-163 121 149 294.5 238.5t371.5 99.5q-8-38-8-74 0-134 94.5-228.5t228.5-94.5q140 0 236 102 109-21 205-78-37 115-142 178 93-10 186-50z">
                  </path>
                </svg>
              </a>
              <a href="#">
                <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="currentColor" class="text-xl transition-colors duration-200 hover:text-gray-800 dark:hover:text-white" viewBox="0 0 1792 1792">
                  <path d="M896 128q209 0 385.5 103t279.5 279.5 103 385.5q0 251-146.5 451.5t-378.5 277.5q-27 5-40-7t-13-30q0-3 .5-76.5t.5-134.5q0-97-52-142 57-6 102.5-18t94-39 81-66.5 53-105 20.5-150.5q0-119-79-206 37-91-8-204-28-9-81 11t-92 44l-38 24q-93-26-192-26t-192 26q-16-11-42.5-27t-83.5-38.5-85-13.5q-45 113-8 204-79 87-79 206 0 85 20.5 150t52.5 105 80.5 67 94 39 102.5 18q-39 36-49 103-21 10-45 15t-57 5-65.5-21.5-55.5-62.5q-19-32-48.5-52t-49.5-24l-20-3q-21 0-29 4.5t-5 11.5 9 14 13 12l7 5q22 10 43.5 38t31.5 51l10 23q13 38 44 61.5t67 30 69.5 7 55.5-3.5l23-4q0 38 .5 88.5t.5 54.5q0 18-13 30t-40 7q-232-77-378.5-277.5t-146.5-451.5q0-209 103-385.5t279.5-279.5 385.5-103zm-477 1103q3-7-7-12-10-3-13 2-3 7 7 12 9 6 13-2zm31 34q7-5-2-16-10-9-16-3-7 5 2 16 10 10 16 3zm30 45q9-7 0-19-8-13-17-6-9 5 0 18t17 7zm42 42q8-8-4-19-12-12-20-3-9 8 4 19 12 12 20 3zm57 25q3-11-13-16-15-4-19 7t13 15q15 6 19-6zm63 5q0-13-17-11-16 0-16 11 0 13 17 11 16 0 16-11zm58-10q-2-11-18-9-16 3-14 15t18 8 14-14z">
                  </path>
                </svg>
              </a>
              <a href="#">
                <svg width="30" height="30" fill="currentColor" class="text-xl transition-colors duration-200 hover:text-gray-800 dark:hover:text-white" viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg">
                  <path d="M477 625v991h-330v-991h330zm21-306q1 73-50.5 122t-135.5 49h-2q-82 0-132-49t-50-122q0-74 51.5-122.5t134.5-48.5 133 48.5 51 122.5zm1166 729v568h-329v-530q0-105-40.5-164.5t-126.5-59.5q-63 0-105.5 34.5t-63.5 85.5q-11 30-11 81v553h-329q2-399 2-647t-1-296l-1-48h329v144h-2q20-32 41-56t56.5-52 87-43.5 114.5-15.5q171 0 275 113.5t104 332.5z">
                  </path>
                </svg>
              </a>
              <a href="#">
                <svg width="30" height="30" fill="currentColor" class="text-xl transition-colors duration-200 hover:text-gray-800 dark:hover:text-white" viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg">
                  <path d="M1551 1476q15-6 26-3t11 17.5-15 33.5q-13 16-44 43.5t-95.5 68-141 74-188 58-229.5 24.5q-119 0-238-31t-209-76.5-172.5-104-132.5-105-84-87.5q-8-9-10-16.5t1-12 8-7 11.5-2 11.5 4.5q192 117 300 166 389 176 799 90 190-40 391-135zm207-115q11 16 2.5 69.5t-28.5 102.5q-34 83-85 124-17 14-26 9t0-24q21-45 44.5-121.5t6.5-98.5q-5-7-15.5-11.5t-27-6-29.5-2.5-35 0-31.5 2-31 3-22.5 2q-6 1-13 1.5t-11 1-8.5 1-7 .5h-10l-3-.5-2-1.5-1.5-3q-6-16 47-40t103-30q46-7 108-1t76 24zm-394-443q0 31 13.5 64t32 58 37.5 46 33 32l13 11-227 224q-40-37-79-75.5t-58-58.5l-19-20q-11-11-25-33-38 59-97.5 102.5t-127.5 63.5-140 23-137.5-21-117.5-65.5-83-113-31-162.5q0-84 28-154t72-116.5 106.5-83 122.5-57 130-34.5 119.5-18.5 99.5-6.5v-127q0-65-21-97-34-53-121-53-6 0-16.5 1t-40.5 12-56 29.5-56 59.5-48 96l-294-27q0-60 22-119t67-113 108-95 151.5-65.5 190.5-24.5q100 0 181 25t129.5 61.5 81 83 45 86 12.5 73.5v589zm-672 21q0 86 70 133 66 44 139 22 84-25 114-123 14-45 14-101v-162q-59 2-111 12t-106.5 33.5-87 71-32.5 114.5z">
                  </path>
                </svg>
              </a>
            </div>
          </div>
          <div class="p-4">
            <div class="mb-4 text-center opacity-90">
              <a href="#" class="relative block">
                <img alt="profil" src="/images/person/3.jpg" class="mx-auto object-cover rounded-full h-40 w-40 " />
              </a>
            </div>
            <div class="text-center">
              <p class="text-2xl text-gray-800 dark:text-white">
                Thierry Halliday
              </p>
              <p class="text-xl font-light text-gray-500 dark:text-gray-200">
                CTO
              </p>
              <p class="max-w-xs py-4 font-light text-gray-500 text-md dark:text-gray-400">
                Thierry Halliday, born November 4, 1993 in Saint hilaire de riez, is css specialist.
              </p>
            </div>
            <div class="flex items-center justify-between pt-8 mx-auto text-gray-500 border-t border-gray-200 w-44">
              <a href="#">
                <svg width="30" height="30" fill="currentColor" class="text-xl transition-colors duration-200 hover:text-gray-800 dark:hover:text-white" viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg">
                  <path d="M1343 12v264h-157q-86 0-116 36t-30 108v189h293l-39 296h-254v759h-306v-759h-255v-296h255v-218q0-186 104-288.5t277-102.5q147 0 228 12z">
                  </path>
                </svg>
              </a>
              <a href="#">
                <svg width="30" height="30" fill="currentColor" class="text-xl transition-colors duration-200 hover:text-gray-800 dark:hover:text-white" viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg">
                  <path d="M1684 408q-67 98-162 167 1 14 1 42 0 130-38 259.5t-115.5 248.5-184.5 210.5-258 146-323 54.5q-271 0-496-145 35 4 78 4 225 0 401-138-105-2-188-64.5t-114-159.5q33 5 61 5 43 0 85-11-112-23-185.5-111.5t-73.5-205.5v-4q68 38 146 41-66-44-105-115t-39-154q0-88 44-163 121 149 294.5 238.5t371.5 99.5q-8-38-8-74 0-134 94.5-228.5t228.5-94.5q140 0 236 102 109-21 205-78-37 115-142 178 93-10 186-50z">
                  </path>
                </svg>
              </a>
              <a href="#">
                <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="currentColor" class="text-xl transition-colors duration-200 hover:text-gray-800 dark:hover:text-white" viewBox="0 0 1792 1792">
                  <path d="M896 128q209 0 385.5 103t279.5 279.5 103 385.5q0 251-146.5 451.5t-378.5 277.5q-27 5-40-7t-13-30q0-3 .5-76.5t.5-134.5q0-97-52-142 57-6 102.5-18t94-39 81-66.5 53-105 20.5-150.5q0-119-79-206 37-91-8-204-28-9-81 11t-92 44l-38 24q-93-26-192-26t-192 26q-16-11-42.5-27t-83.5-38.5-85-13.5q-45 113-8 204-79 87-79 206 0 85 20.5 150t52.5 105 80.5 67 94 39 102.5 18q-39 36-49 103-21 10-45 15t-57 5-65.5-21.5-55.5-62.5q-19-32-48.5-52t-49.5-24l-20-3q-21 0-29 4.5t-5 11.5 9 14 13 12l7 5q22 10 43.5 38t31.5 51l10 23q13 38 44 61.5t67 30 69.5 7 55.5-3.5l23-4q0 38 .5 88.5t.5 54.5q0 18-13 30t-40 7q-232-77-378.5-277.5t-146.5-451.5q0-209 103-385.5t279.5-279.5 385.5-103zm-477 1103q3-7-7-12-10-3-13 2-3 7 7 12 9 6 13-2zm31 34q7-5-2-16-10-9-16-3-7 5 2 16 10 10 16 3zm30 45q9-7 0-19-8-13-17-6-9 5 0 18t17 7zm42 42q8-8-4-19-12-12-20-3-9 8 4 19 12 12 20 3zm57 25q3-11-13-16-15-4-19 7t13 15q15 6 19-6zm63 5q0-13-17-11-16 0-16 11 0 13 17 11 16 0 16-11zm58-10q-2-11-18-9-16 3-14 15t18 8 14-14z">
                  </path>
                </svg>
              </a>
              <a href="#">
                <svg width="30" height="30" fill="currentColor" class="text-xl transition-colors duration-200 hover:text-gray-800 dark:hover:text-white" viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg">
                  <path d="M477 625v991h-330v-991h330zm21-306q1 73-50.5 122t-135.5 49h-2q-82 0-132-49t-50-122q0-74 51.5-122.5t134.5-48.5 133 48.5 51 122.5zm1166 729v568h-329v-530q0-105-40.5-164.5t-126.5-59.5q-63 0-105.5 34.5t-63.5 85.5q-11 30-11 81v553h-329q2-399 2-647t-1-296l-1-48h329v144h-2q20-32 41-56t56.5-52 87-43.5 114.5-15.5q171 0 275 113.5t104 332.5z">
                  </path>
                </svg>
              </a>
              <a href="#">
                <svg width="30" height="30" fill="currentColor" class="text-xl transition-colors duration-200 hover:text-gray-800 dark:hover:text-white" viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg">
                  <path d="M1551 1476q15-6 26-3t11 17.5-15 33.5q-13 16-44 43.5t-95.5 68-141 74-188 58-229.5 24.5q-119 0-238-31t-209-76.5-172.5-104-132.5-105-84-87.5q-8-9-10-16.5t1-12 8-7 11.5-2 11.5 4.5q192 117 300 166 389 176 799 90 190-40 391-135zm207-115q11 16 2.5 69.5t-28.5 102.5q-34 83-85 124-17 14-26 9t0-24q21-45 44.5-121.5t6.5-98.5q-5-7-15.5-11.5t-27-6-29.5-2.5-35 0-31.5 2-31 3-22.5 2q-6 1-13 1.5t-11 1-8.5 1-7 .5h-10l-3-.5-2-1.5-1.5-3q-6-16 47-40t103-30q46-7 108-1t76 24zm-394-443q0 31 13.5 64t32 58 37.5 46 33 32l13 11-227 224q-40-37-79-75.5t-58-58.5l-19-20q-11-11-25-33-38 59-97.5 102.5t-127.5 63.5-140 23-137.5-21-117.5-65.5-83-113-31-162.5q0-84 28-154t72-116.5 106.5-83 122.5-57 130-34.5 119.5-18.5 99.5-6.5v-127q0-65-21-97-34-53-121-53-6 0-16.5 1t-40.5 12-56 29.5-56 59.5-48 96l-294-27q0-60 22-119t67-113 108-95 151.5-65.5 190.5-24.5q100 0 181 25t129.5 61.5 81 83 45 86 12.5 73.5v589zm-672 21q0 86 70 133 66 44 139 22 84-25 114-123 14-45 14-101v-162q-59 2-111 12t-106.5 33.5-87 71-32.5 114.5z">
                  </path>
                </svg>
              </a>
            </div>
          </div>
        </div>
      </div> */}


    </>
  )
}

export default App

export const users = [
  {
    name: "Manu Arora",
    designation: "Founder, Algochurn",
    image: "https://picsum.photos/id/10/300/300",
    badge: "Mentor",
  },
  {
    name: "Sarah Singh",
    designation: "Founder, Sarah's Kitchen",
    image: "https://picsum.photos/id/11/300/300",
    badge: "Mentor",
  },
  {
    name: "John Doe",
    designation: "Software Engineer, Tech Corp",
    image: "https://picsum.photos/id/12/300/300",
    badge: "Mentor",
  },
  {
    name: "Jane Smith",
    designation: "Product Manager, Innovate Inc",
    image: "https://picsum.photos/id/13/300/300",
    badge: "Mentor",
  },
  {
    name: "Robert Johnson",
    designation: "Data Scientist, DataWorks",
    image: "https://picsum.photos/id/14/300/300",
    badge: "Mentor",
  },
  {
    name: "Emily Davis",
    designation: "UX Designer, DesignHub",
    image: "https://picsum.photos/id/15/300/300",
    badge: "Mentor",
  },
  {
    name: "Michael Miller",
    designation: "CTO, FutureTech",
    image: "https://picsum.photos/id/16/300/300",
    badge: "Mentor",
  },
  {
    name: "Sarah Brown",
    designation: "CEO, StartUp",
    image: "https://picsum.photos/id/17/300/300",
  },
  {
    name: "James Wilson",
    designation: "DevOps Engineer, CloudNet",
    image: "https://picsum.photos/id/18/300/300",
    badge: "Something",
  },
  {
    name: "Patricia Moore",
    designation: "Marketing Manager, MarketGrowth",
    image: "https://picsum.photos/id/19/300/300",
    badge: "Mentor",
  },
  {
    name: "Richard Taylor",
    designation: "Frontend Developer, WebSolutions",
    image: "https://picsum.photos/id/20/300/300",
  },
  {
    name: "Linda Anderson",
    designation: "Backend Developer, ServerSecure",
    image: "https://picsum.photos/id/21/300/300",
  },
  {
    name: "William Thomas",
    designation: "Full Stack Developer, FullStack",
    image: "https://picsum.photos/id/22/300/300",
    badge: "Badger",
  },
  {
    name: "Elizabeth Jackson",
    designation: "Project Manager, ProManage",
    image: "https://picsum.photos/id/23/300/300",
    badge: "Mentor",
  },
  {
    name: "David White",
    designation: "Database Administrator, DataSafe",
    image: "https://picsum.photos/id/24/300/300",
    badge: "Advocate",
  },
  {
    name: "Jennifer Harris",
    designation: "Network Engineer, NetConnect",
    image: "https://picsum.photos/id/25/300/300",
  },
  {
    name: "Charles Clark",
    designation: "Security Analyst, SecureIT",
    image: "https://picsum.photos/id/26/300/300",
  },
  {
    name: "Susan Lewis",
    designation: "Systems Analyst, SysAnalyse",
    image: "https://picsum.photos/id/27/300/300",
  },
  {
    name: "Joseph Young",
    designation: "Mobile Developer, AppDev",
    image: "https://picsum.photos/id/28/300/300",
    badge: "Mentor",
  },
  {
    name: "Margaret Hall",
    designation: "Quality Assurance, BugFree",
    image: "https://picsum.photos/id/29/300/300",
    badge: "Developer",
  },
];
