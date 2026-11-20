# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '5d525ee305af66b9e2434178358b9d7f789cfd6f',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '8afcda85258fc6497a9304c9abbed42b1ddd0478',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '50184103b19027f5c7080060712d6a9470cf59ee',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '8903ea3e94370b9341cfe7c95a8274b3ae783b1b',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'd277a0a3cda9c682708c93279f0c72cd6b0ae3f3',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'bdeb6dc40fe4330a7dda0aa630a5b80c65c5f8f3',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '1d3fbab1ff5abce9f3eb9f3e7fcf66f455ae4475',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '9f11befc94670d692521529fad93429655dd4083',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '775de90a4d7b509680908a738bea0bc6cb171a93',
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
