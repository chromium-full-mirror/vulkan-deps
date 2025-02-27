# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '0b7c079b32f676b57e92a8ded374976842985116',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'f82d29981c0b0136adfaa7863df485a705c80c84',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '54a521dd130ae1b2f38fef79b09515702d135bdd',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'd3bfa4b9b639c47ffaee7c1c1b76044c92fa66cc',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '952f776f6573aafbb62ea717d871cd1d6816c387',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '809941a4ca137df69dc9c6e8eb456bd70309197c',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'fb8f5a5d69f4590ff1f5ecacb5e3957b6d11daee',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '2d8f273ebd4b843c402d9ee881616895b854e42f',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '4e7b0c905b1a0401e24333800937cc8792efa037',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
