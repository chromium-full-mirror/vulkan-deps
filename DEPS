# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '37b5bd7264c2c4acfa6f11826c29a16ab6a2a699',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '98254945250cdf47d66779d427bed964071d7271',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '86f980c731e62ae4eaf383d320449d71687936bf',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'e56740d931256cc464d4d1a76149f69469c33f70',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'c46850864f4661461b0f6cb9922c058ffea4915e',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '6a5ae1ea5f55d52be776663dc7f765f5a8502e4c',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '253565dc0d93503d0cdd0e061eababc9bb43b71f',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '90738f6edfa19561a978fc5f97543ba37075ba9d',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '75a29e75cc376913427fe13620478bf64e636201',
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
