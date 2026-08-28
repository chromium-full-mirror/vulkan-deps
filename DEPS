# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '23076b376e06a99b4c765df5c9836d127c8bbbfc',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'afefb1e880c825d80ee4c2faf326721092ac3025',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '496543121ce6419f23d6fa5d7194ba66c36212d2',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'd7ca4efbbe36709fc49e1a102cdbe1d970d5eb7e',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '31386378257ac8653ce5b32c93baec385259ebbe',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'd38ce70f36b77daeea003cd33ad04eac718bd9b0',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'af0452ed9eedc16acbe58ef378177057d67a8d84',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '634022187b2cd1e02e4793e75cdc569ed90e1f51',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '289a87f921ccc9c986dccbdee1ada66dc696d29e',
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
