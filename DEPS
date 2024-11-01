# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'd81aeef9f82050bd5940ce1c475d8316ad41d747',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'a251560a3f1ea56fb5b1d32667d2df6e83e06eda',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'cb6b2c32dbfc3257c1e9142a116fe9ee3d9b80a2',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'e5c1498afa1daa8cf3a48af7a74e3b7429afb05d',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'f2eb740f3f0340ad941e563484d5ba45a5ec6af0',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '9276d73f29651c92402f0f0389108d69bb51b9ca',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'e94085e2167e33b6b18474da24ff18f46bc56976',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '9123b8c04b378c1b81899314e3060a80f255a24b',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'b8093e3a1854285cbd183fa98b410090889fa500',
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
