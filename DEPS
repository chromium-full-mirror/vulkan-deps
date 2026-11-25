# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '6334e1549a49989e04b5329a6a39a328247fd6ed',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '328bbcab55f742075528906f1260606a28f9bcfa',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'a9a66db4dcdff79915e667bd2bd1bffe3d1fb2d7',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '340b4c41f92610d914abbf3754ba2354856a580f',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'd277a0a3cda9c682708c93279f0c72cd6b0ae3f3',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '7d76ff3c3eac272ed37f606e13915b3bd288c30b',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '01d98ef3721bf2a3bf5a1b09ba24b43eb2232fa8',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '92ff93e94cbf0244336720ed98cbfdc2c84d5350',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'f3176470ab775fe826d16ed717e455295b954096',
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
