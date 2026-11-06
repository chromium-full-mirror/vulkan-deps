# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '83f75db6ada23801a65eed1cde4763a0a5bfbda6',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'f3353fc09adcf02a6524e2101c0ee2c17d91a140',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '6efe5ae6b7c6ad29da3f2cc3f164b9c3d72b78b1',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'b570f00a782a7bf4006964e8284dd8c10c4c549b',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '88487f687f3100ebe1d3559a8a34d971ee85b977',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '385c80c6f64ef4608ce5e2c2067d1765ab503c98',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'bfac990e5eaed6acc4ba217e25d305cabd408740',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '271510bc50a1ecc65e62ca07dbf6b8dfe530dfd0',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '3159ec512ff2b3a7780d076db33a7bc1b582cd3b',
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
