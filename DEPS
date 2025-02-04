# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '39766a06679bf5e4bc1e0339136f1b6a519fcec5',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '5728a66537b23986135f50c465fcb282b0434da4',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'e7294a8ebed84f8c5bd3686c68dbe12a4e65b644',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '9d07794bc955101c79cbd260233fcc65b9951cfc',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '39f924b810e561fd86b2558b6711ca68d4363f68',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'fde0f9718bd60b49cf8efc80d3fb7a093c309ac0',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'c52931f012cb7b48e42bbf2050a7fb2183b76406',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'fe7a09b13899c5c77d956fa310286f7a7eb2c4ed',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'ee449af5b3d081d2dbdf4e8b741dd520b3bfeb49',
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
