<template>
  <div class="design-system h-full p-4 flex flex-col">
    <section>
      <h1 class="m-0">Design System Canvas</h1>
    </section>

    <section class="b-3 flex-1 flex flex-col">
      <ul class="list-none flex flex-1">
        <li class="flex-1 p-4 b-r-3 b-b-3">
          <strong>1. PROBLEM(遇到的问题)</strong>
          <p class="text-xs opacity-40">What are the problems you currently face with your approach to designing new products and services?</p>
        </li>

        <li class="flex-1 p-4 b-r-3 b-b-3">
          <strong>2. Existing assets(现有的资源)</strong>
          <p class="text-xs opacity-40">What assets do you have already that could be folded in? Think about component libraries, style guides,
            marketing assets and more.</p>
        </li>

        <li class="flex-1 p-4 b-b-3">
          <strong>3. Maturity level(资源成熟度)</strong>
          <p class="text-xs opacity-40">Based on what exists, what maturity level are you at?</p>
        </li>
      </ul>

      <ul class="list-none flex flex-1">
        <li class="flex-1 p-4 b-r-3 b-b-3">
          <strong>4. New resources(新的资源)</strong>
          <p class="text-xs opacity-40">What new things need to be put in place, in order to move your design system up a maturity level?</p>

          <ul class="list-none flex">
            <li class="flex-1 p-4 b-r-3">
              <strong>4a. Assets(资源)</strong>
            </li>
            <li class="flex-1 p-4">
              <strong>4b. Processes(进度)</strong>
            </li>
          </ul>
        </li>

        <li class="flex-1 p-4 b-r-3 b-b-3">
          <strong>5. Affected products(受影响的产品)</strong>
          <p class="text-xs opacity-40">Who are the stakeholders? Who will be using the design system? Who will be contributing to it?</p>
        </li>

        <li class="flex-1 p-4 b-b-3">
          <strong>6. Consumers(谁会使用这个产品)</strong>
          <p class="text-xs opacity-40">What constraints do you have? What are the limitations of the design system?</p>

          <ul class="list-none flex b-t-3">
            <li class="flex-1 p-4 b-r-3">
              <strong>7a. Maintainers(谁来更新这个产品)</strong>
              <p class="text-xs opacity-40">Who will maintain it?</p>
            </li>
            <li class="flex-1 p-4">
              <strong>7b. Champions(谁来捍卫这个产品)</strong>
              <p class="text-xs opacity-40">Who will champion it?</p>
            </li>
          </ul>
        </li>
      </ul>

      <ul class="list-none flex flex-1">
        <li class="flex-1 p-4 b-r-3">
          <strong>8. Scope(范围)</strong>
          <p class="text-xs opacity-40">What scope of changes is feasible and realistic?</p>
        </li>

        <li class="flex-1 p-4 b-r-3">
          <strong>9. Adoption strategy(采用的策略)</strong>
          <p class="text-xs opacity-40">What needs to happen for the design system to be adopted by the
            consumers? Who will own making that happen?
          </p>
        </li>

        <li class="flex-1 p-4">
          <strong>10. Costs(成本)</strong>
          <p class="text-xs opacity-40">What will this cost? Consider what resources will be needed team capacity, time and money.</p>
        </li>
      </ul>
    </section>
  </div>
</template>
