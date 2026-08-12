# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '2c8d5be1153383e7a3ee6b5b7ea41fa551771120',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '5ce04fabf196c57af002e1d6fbdb2f1e339a89d1',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'f0bf307f7c49d26484db596185cece53c37701fc',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '29174bd16335bb1404466ee59dad4fc7bf51efb3',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'f9973cd97e6f3584707e7ef1c425e336f1b92a5b',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '17e951696c677f35c7e8671108a70a2a112d939f',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '572d10d787b74601ea09b696521c950c259ae815',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '120d418dd8fa884c82c783578ca381d2c81c92c9',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '8855fa01d7779c5ddf4fc3dfe0932cf6bd7c2552',
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
