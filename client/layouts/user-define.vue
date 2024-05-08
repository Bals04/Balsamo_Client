<template>
    <div class="flex justify-between items-center w-auto h-20 bg-gray-900 px-4">
      <div class="flex space-x-4">
        <div @click="navigateTo('/')" class="px-4 py-2 bg-white text-gray-900 rounded-md cursor-pointer">ZeeZee.org</div>
      </div>
      <Label></Label>
      <div class="flex space-x-4">
        <ContactsBtn></ContactsBtn>
        <ServicesButton></ServicesButton>
        <LocationBtn></LocationBtn>
        <Button></Button>
      </div>
    </div>
  </template>
  