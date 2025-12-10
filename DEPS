# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '0036567adc7961f55a65a518bf5e303a4d4650c4',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '031011bb2a278a972b0b457e15cb077ae98434cf',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '6146b3d9ad4fcc5fb512209d348e97ce03749169',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '4ba51944c702f2168934f4fce6dab48d53792530',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '2fa203425eb4af9dfc6b03f97ef72b0b5bcb8350',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '002a13d8f9bcca69e4efc7911492c4ac1c981698',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '2170c33bb3d2af976a1894666bfd3dc80cbe4da8',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'c010c19e796035e92fb3b0462cb887518a41a7c1',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '010ea35d049edec185afb1855b7b9c2c36d96ad8',
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
